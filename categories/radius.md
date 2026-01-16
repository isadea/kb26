## Metadata_Start 
## code: en
## title: RADIUS 
## slug: radius 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## 
## What is {{variable.RADIUS}}?
{{variable.RADIUS}} is a server-based method to control who can connect to your Wi-Fi network. It can help you check your customers in automatically in Nexudus when they log in to your network.

## How the {{variable.RADIUS}} Integration Works
You need a controller that's within the supported controller list in IronWiFi: [https://www.ironwifi.com/list-of-supported-vendors]( https://www.ironwifi.com/list-of-supported-vendors){target="_blank"}.

Before configuring your controller, you also need a {{variable.RADIUS}} server license. You need a {{variable.RADIUS}} server license for each Wi-Fi access point you plan on having in your space. You must get your license through {{variable.Nexudus}} to use the integration. 

:::(Warning) ({{variable.RADIUS}} licenses have a minimum charge of {{variable.Radius_MinimumPrice}}. )
This minimum charge includes 5 access points by default. Each additional access point costs {{variable.Radius_APPrice}}. 
:::

Just {{variable.ContactSupport}} to request a license, making sure you include the name of your controller vendor.

Each license comes with two geographically redundant servers for *{{variable.RADIUS}} Authentication* and *{{variable.RADIUS}} Accounting*. We create these as close as possible to your physical location based on the data centers we have available.

Once you have your license, you can set up your controller and enable the integration in {{variable.Nexudus}}. 

{{variable.MoreInformation}} [Integrating {{variable.RADIUS}}](/v3/docs/integrating-radius){target="_blank"}.

:::(error) (We cannot provide support to set up or troubleshoot your network.)
The instructions we provide are guidelines to help you connect your network infrastructure to {{variable.Nexudus}}, but we strongly recommend hiring professionals with experience setting up server-based Wi-Fi networks.
:::

* * *
{{snippet.FAQ_RADIUS}}