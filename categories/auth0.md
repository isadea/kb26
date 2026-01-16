## Metadata_Start 
## code: en
## title: Auth0 
## slug: auth0 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## What is {{variable.Auth0}}? 
{{variable.Auth0}}’s identity and management platform lets your users log in to the {{variable.MembersPortal}} or {{variable.AdminPanel}} using enterprise federation, social login, or username and password authentication instead of the default credentials Nexudus provides when you register them. 

## How {{variable.Auth0}} works 

You need an {{variable.Auth0}} account that supports {{variable.OpenId}} authentication. Nexudus connects your {{variable.Auth0}} application through the {{variable.OpenId}} integration on the {{variable.AdminPanel}}, which means it is crucial that your application support the {{variable.OpenId}} authentication protocol.

You also need the following details from your {{variable.Auth0}} account: 
* Log out URL
* Authority URL
* Client ID
* Client Secret

You should be able to find all this information within your {{variable.Auth0}} application. Once you've [integrated {{variable.Auth0}}](/v3/docs/integrating-auth0){target="_blank"}, users should be able to log in using enterprise federation, social login, or username and password authentication instead of the default credentials Nexudus provides when you register them.