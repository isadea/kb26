## Metadata_Start 
## code: en
## title: Single Sign-On (SSO) 
## slug: user-authentication 
## seoTitle: Single Sign-On (SSO) 
## description: SSO  
## contentType: Markdown 
## Metadata_End
## What is SSO (Single sign-on)? 
Single sign-on is an identification method that lets users to log in to multiple platforms and websites using a single set of credentials. In Nexudus, this means allowing customers and admins to log in using credentials that aren't the ones provided by Nexudus. 

*For example, letting your customers log in to the {{variable.MembersPortal}} and the Passport app using their Outlook email and password or letting admins log in to the {{variable.AdminPanel}} using credentials from your active directory.* 

## How SSO Integrations Work
Enabling a SSO integration lets your customers log in to the {{variable.MembersPortal}} and the Passport app using credentials from your own directory or a third-party like Google or Outlook if you're using Okta. It also lets your admins log in to the {{variable.AdminPanel}} using these credentials instead of the ones assigned by Nexudus. 

It lets all users, customers and admins alike, log in to their side of Nexudus using external credentials. 

*For example, you can let customers log in to the {{variable.MembersPortal}} using their Google account instead of their Nexudus credentials.* 

SSO integration settings let you define if you only want to allow log-ins through your SSO provider or if you'd like to let users choose to log in using either SSO or their Nexudus credentials. 

You can also define what happens to users trying to log in without an admin or customer account in Nexudus. You choose to automatically create a customer account for them as they try to log in or simply deny access to the platforms. 

## Available SSO Integrations
Nexudus integrates with the following SSO options: 

* [Azure AD](/v3/docs/azure-ad){target="_blank"} 
* [{{variable.AzureADB2C}}](/v3/docs/integrating-azure-ad-b2c){target="_blank"}
* [LDAP ](/v3/docs/ldap){target="_blank"}
* [Okta](/v3/docs/okta){target="_blank"}
* [Auth0](/v3/docs/auth0){target="_blank"}
* [OpenID](/v3/docs/openid){target="_blank"}


[Azure AD](/v3/docs/azure-ad){target="_blank"}, [{{variable.AzureADB2C}}](/v3/docs/azure-ad-b2c){target="_blank"}, [LDAP](/v3/docs/ldap){target="_blank"}, [Auth0](/v3/docs/auth0){target="_blank"} and [OpenID](/v3/docs/openid){target="_blank"} require you to have a directory already set up. If you'd like your users to log in using credentials from other providers, we recommend you pick [Okta](/v3/docs/okta){target="_blank"}.

* * *

## FAQ 
### Is SSO available on the {{variable.AdminPanel}}? 
Yes! Enabling any SSO integration in Nexudus automatically lets all its users connect using their directory or third-party provider credentials. This includes admins logging in to the {{variable.AdminPanel}} and customers logging in to the {{variable.MembersPortal}} or the Passport app. 

### Can I use a different SSO integrations for the {{variable.MembersPortal}} and the {{variable.AdminPanel}}? 
The short answer is no, you should only enable one SSO integration at a time that applies to all sides of the Nexudus platform. You can work around this limitation and have different SSO integrations to work on each side of the platform, but this requires extensive customization and an infrastructure that allows you to self-host your {{variable.MembersPortal}}. 




