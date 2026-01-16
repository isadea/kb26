## Metadata_Start 
## code: en
## title: Azure AD 
## slug: azure-ad 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## What is Azure Active Directory?
Azure Active Directory, also known as {{variable.AzureAD}}, is an access directory service offered as part of Microsoft Azure cloud services that helps your customers log in to the {{variable.MembersPortal}} and {{variable.Nexudus}} apps using external user credentials and secure customer authentication.

## How the {{variable.AzureAD}} integration works
You first need to set up your inventory in {{variable.AzureAD}}. Once your directory is set up in {{variable.AzureAD}}, you need to enable the {{variable.AzureAD}} integration {{variable.OnTheAdminPanel}}. You can choose to allow customers to log in using 


Once both are completed, any user in Azure AD trying to log in to your Members Portal should be able to log in , your users are able to log in using the same credentials they use to access your organisation's network.

## How users can acccess your {{variable.MembersPortal}} with {{variable.AzureAD}}
If the user trying to log in to your {{variable.MembersPortal}} using Azure credentials isn't a customer in {{variable.Nexudus}} yet, we will automatically create a contact for them the first time they log in. 