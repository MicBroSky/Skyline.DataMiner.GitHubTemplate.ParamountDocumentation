---
uid: <PRJID>_overview_access
---

# Access Overview

> ### Attention 🚨
> Access credentials should be stored in the [Skyline Password Manager](https://passwords.skyline.be/).

> ### Access via VPN client and credentials
> * Open a web browser and navigate to this webpage:  [vpn.gb.vimn.com/vendormfa-okta](vpn.gb.vimn.com/vendormfa-okta).

> ![cisco_ssl_vpn_service.png](../../images/Paramount/cisco_ssl_vpn_service.png)

> * Login using the credentials with the email address as the username available on [Skyline Password Manager](https://passwords.skyline.be/) for the "Paramount" customer.
> * You are given two options to authenticate using Two Factor Aunthentication: activate a push by inserting "1" or insert the code provided by the "Okta Verify" app.

> ![cisco_ssl_vpn_service_2fa.png](../../images/Paramount/cisco_ssl_vpn_service_2fa.png)

> * After successful authentication, it should send you to a screen titled "AnyConnect Secure Mobility Client". You can install the AnyConnect VPN exe on your computer by clicking the link it provides.
> ![cisco_anyconnect_download.png](../../images/Paramount/cisco_anyconnect_download.png)
> * Once the AnyConnect Secure Mobility CLient is installed, you need to make the connection endpoint be "vpn.gb.vimn.com/vendormfa-okta".
> ![cisco_anyconnect_example.png](../../images/Paramount/cisco_anyconnect_example.png)
> * Once you press "Connect", you'll be prompted to first put in the password of the account, and then do one of the Two Factor Authentication options just like with the website.

> ![cisco_anyconnect_credentials.png](../../images/Paramount/cisco_anyconnect_credentials.png)

> ![cisco_anyconnect_2fa.png](../../images/Paramount/cisco_anyconnect_2fa.png)

> * After successful VPN connection, you can use DataMiner Cube to connect directly to the Production or Staging Cluster. 

> ![dataminercube_paramount_endpoints.png](../../images/Paramount/dataminercube_paramount_endpoints.png)

> * You can also RDP to the Production cluster and on that computer RDP to other computers within that cluster. It is also possible to RDP to the Staging cluster.