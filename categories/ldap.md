## Metadata_Start 
## code: en
## title: LDAP 
## slug: ldap 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## 
## What is LDAP? 
LDAP (**L**ightweight **D**irectory **A**ccess **P**rotocol) is a protocol that allows authenticated communication between applications (in this case Nexudus) and directory services servers. 
:::(Info) (What are directory services?)
Directory services store the users, passwords, and computer accounts, and share that information with other parties.
:::
Provided you already have a directory service, all you need to enable the integration. Once the integration is enabled, regular {{variable.MembersPortal}} credentials won't work and all {{variable.customers}} will need to log in using their directory credentials. 

## How the LDAP integration works

The LDAP integration lets your directory users log in to your {{variable.MembersPortal}} using their directory credentials. 

Whenever a user tries to log in to the {{variable.MembersPortal}} using directory credentials, {{variable.Nexudus}} will communicate with your directory's server using LDAP to check if the user's credentials match a directory profile.

If the user doesn't exist in your directory, they won't be able to access to the {{variable.MembersPortal}}. If the credentials match a directory profile, {{variable.Nexudus}} will grant or deny access to the {{variable.MembersPortal}} based on the *Provision new users if they don't exist* setting you've defined while setting up the integration.

{{variable.MoreInformation}} [Integrating LDAP](/docs/integrating-ldap){target=`_blank`}.