<!--TEMPLATE_VERSION=1.0.0-->
# Documentation Repository

Welcome to our Basic Documentation Project Repository! 🚀

## Overview

This base repository, aligned with OKR Q1 2025, offers a clear structure and initial content that DevOps professionals can utilize to create fundamental documentation for a delivery project.

Basic documentation refers to the minimum content required to be considered delivered:

1. An **overview** section containing information about the access mechanism and other technical documentation, typically created during the deployment phase.

2. The **deployment** section includes a description of the high-level architecture and an inventory of the infrastructure.

> [NOTE]
> Every new project **must have** basic documentation, and it is imperative that sales account for the effort required during the offering phase.


## Why Documentation Matters

Documentation provides a shared understanding and knowledge base for our team and our customers. It serves as a reference point, enabling us to:

- **Improve Collaboration:** Working together with customers on documentation ensures we capture their unique perspectives and requirements, leading to better solutions.
- **Ensure Clarity:** Having a clear overview from the beginning helps us build a strong foundation, reducing confusion and misunderstandings.
- **Enhance Customer Experience:** Well-documented processes and products empower our customers, enabling them to use our solutions effectively.

## How to use this repository

The repository is designed to serve as a foundational content structure that can later be integrated into our [internal project documentation](https://internaldocs.skyline.be/Projects/Projects.html). Although it may seem redundant at first glance, it’s important to note that the following instructions are intended only for new documentation efforts or when we want to overhaul existing documentation. Ultimately, this process greatly justifies the effort involved:

1. Clone this repository to establish the documentation structure, which will later be integrated into the internal-docs repository.
> [NOTE] After integrating the initial content into internal-docs, this cloned repository should no longer be used for future changes. Instead, all modifications should be made directly within internal-docs.
2. The repository uses several placeholders between '< >' characters. Find and replace these with the appropriate values for the project being documented.
> [IMPORTANT] A special placeholder between _\<PRJID\>_ was used to create the **uid** references of the provided articles. You **must** find and replace all instances of this placeholder with a string that uniquely identifies the project being documented. Ensure that you use only characters permissible for creating UID references (for example, replacing \<PRJID\> with GCPVO123).
3. Rename the default project name _PRJNAME_ within the Projects and images folders with the name of the new project under documentation
> [IMPORTANT] If you want to use a folder name with multiple words, use an underscore "_" character (e.g., My_Great_Project) instead of space to avoid problems referencing the materials (e.g., images) with Markdown links. If spaces are preferred, you may need to wrap the path between '<' and '>' characters or use %20 to escape the spaces
4. Update existing articles or add new ones, ensuring the toc.yml file is properly referencing the new articles.
4. Build and test the project by using the _Docfx build_ command
5. When you are confident that the documentation is ready for integration, please follow the instructions below

### How to integrate into internal docs
1. Follow our guidelines to collaborate on the documentation, which typically requires creating a fork of internal docs
2. Create a new folder in the Projects directory with a name that intuitively identifies your project
3. Copy the contents of the project and images folders from your documentation repository into the new folder in the forked project
4. Stage all new folders and files so they are ready to commit 
5. Edit the _toc.yml_ file located in the Project's root folder and add a new section in the correct position, following the alphabetical order of the other projects:
> -name: Test Project
> 
> href: Test Project/toc.yml

6. Build and test the fork project by using the Docfx build command
7. Ensure that your new project documentation aligns correctly with existing projects. Make adjustments as needed
8. Commit the changes and create a pull request to have a final documentation merge into the main branch at internal docs

## Let's Build Something Great Together!

Thank you for contributing to our documentation efforts. By collaborating, adding new content, and maintaining the existing resources, we can create a knowledge base that benefits everyone. Together, let's build exceptional products, provide outstanding support, and deliver an exceptional experience to our customers.

Happy documenting! 📚✨
