# Documentation Repository

Welcome to our Basic Documentation Project Repository! 🚀

## Overview

This repository template, aligned with OKR Q1 2025, offers a clear structure and initial content that DevOps professionals can utilize to create fundamental documentation for a delivery project.

Basic documentation refers to the minimum content required to be considered delivered:

1. An **overview** section containing information about the access mechanism and other technical documentation, typically created during the deployment phase.

2. The **deployment** section includes a description of the high-level architecture and an inventory of the infrastructure.

> [!NOTE]
> Every new project **must have** basic documentation, and it is imperative that sales account for the effort required during the offering phase.


## Why Documentation Matters

Documentation provides a shared understanding and knowledge base for our team and our customers. It serves as a reference point, enabling us to:

- **Improve Collaboration:** Working together with customers on documentation ensures we capture their unique perspectives and requirements, leading to better solutions.
- **Ensure Clarity:** Having a clear overview from the beginning helps us build a strong foundation, reducing confusion and misunderstandings.
- **Enhance Customer Experience:** Well-documented processes and products empower our customers, enabling them to use our solutions effectively.

## How to use this template

The template is designed to serve as a foundational repository that can later be integrated into our [internal project documentation](https://internaldocs.skyline.be/Projects/Projects.html). Although it may seem redundant at first glance, it’s important to note that the following instructions are intended only for new documentation efforts or when we want to overhaul existing documentation. Ultimately, this process greatly justifies the effort involved:

1. Follow the steps described at [Creating a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)
2. The template uses several placeholders between '{{ }}' characters. Find and replace these with the appropriate values for the project being documented.
> [!IMPORTANT] A special placeholder between _\<PRJID\>_ was used to create the **uid** references of the provided articles. You **must** find and replace all instances of this placeholder with a string that uniquely identifies the project being documented. Ensure that you use only characters permissible for creating UID references (for example, replacing \<PRJID\> with GCPVO123).
3. Update existing articles or add new ones, ensuring the toc.yml file is properly referencing the new articles.
4. Build and test the project by using the _Docfx build_ command
5. When you are confident that the documentation is ready for integration, please follow the instructions below

### How to integrate into internal docs
1. Follow our guidelines to collaborate on the documentation, which typically requires creating a fork of internal docs
2. Create a new folder in the Projects directory with a name that intuitively identifies your project
3. Copy the contents of the _articles_ and _images_ folders from your documentation repository into the new folder in the forked project
4. Stage all new folders and files so they are ready to commit 
5. Edit the _toc.yml_ file located in the Project's root folder and add a new section in the correct position, following the alphabetical order of the other projects:
> -name: Test Project
> 
> href: Test Project/articles/toc.yml

6. Build and test the fork project by using the Docfx build command
7. Ensure that your new project documentation aligns correctly with existing projects. Make adjustments as needed
8. Commit the changes and create a pull request to have a final documentation merge into the main branch at internal docs
> ℹ️ Once the new project has been integrated into the internal docs documentation repository any further addition shall be done by using the internal docs repository, and therefore you are free to delete the initial repository created from this template.

## Let's Build Something Great Together!

Thank you for contributing to our documentation efforts. By collaborating, adding new content, and maintaining the existing resources, we can create a knowledge base that benefits everyone. Together, let's build exceptional products, provide outstanding support, and deliver an exceptional experience to our customers.

Happy documenting! 📚✨
