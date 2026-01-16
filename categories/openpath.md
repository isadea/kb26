## Metadata_Start 
## code: en
## title: Avigilon Alta (formerly OpenPath) 
## slug: openpath 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## 
## What is {{variable.OpenPath}} (formerly OpenPath)? 
{{variable.OpenPath}}, formerly known as OpenPath, is a door access control system that lets your {{variable.customers}} autonomously unlock doors and access different areas of your space using access cards. Their access is based on their {{variable.passes}}, bookings, {{variable.product}} purchases, and active {{variable.contracts}}.

![OpenPth_Image.jpg](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/OpenPth_Image.jpg){height="500" width=""}

:::(Warning) (Using {{variable.OpenPath}} adds a monthly {{variable.Currencies}} 50 charge to your {{variable.Nexudus}} subscription, per {{variable.location}} enabled.)
:::
## How the {{variable.OpenPath}} Integration Works

The {{variable.OpenPath}} integration automatically grants access to your space using {{variable.OpenPath}} access groups and several inventory items you have in {{variable.Nexudus}}. You can connect {{variable.OpenPath}} access groups to: 

* {{variable.resources}}
* {{variable.passes}}
* desks and offices

You need to create **one access group per Nexudus item** you want to connect to  {{variable.OpenPath}}. Each access group should include all the doors {{variable.customers}} need to unlock to move around your space. 

*For example, if you want to connect a {{variable.resource}} to {{variable.OpenPath}}, you should create a dedicated access group that includes all the doors a {{variable.customer}} needs to open in order to get to the {{variable.resource}}.*

Once you have all the relevant access groups in {{variable.OpenPath}}, you can enable the integration in {{variable.Nexudus}} and connect each relevant inventory item to its corresponding access group. 

{{variable.Customers_CAP}} who book the connected {{variable.resources}}, get {{variable.passes}}, or have a desk/office assigned to one of their {{variable.contracts}} are then automatically able to open the doors included in the {{variable.OpenPath}} access group you connected to the relevant {{variable.Nexudus}} items. They are able to unlock the relevant doors using their {{variable.OpenPath}} access card. 

{{variable.MoreInformation}} [Integrating {{variable.OpenPath}}](/v3/docs/integrating-openpath){target="_blank"}.

* * *
## FAQ

### Can my customers use {{variable.OpenPath}} mobile passes to unlock doors? 
Yes, customers can currently only unlock doors using {{variable.OpenPath}} access cards, also known as [encrypted credentials](https://www.openpath.com/access-methods#encrypted-credentials){target="_blank"}, Avigilon Alta's app, and the {{variable.WLApp}} if your space uses it. 

### How many access groups should I create in {{variable.OpenPath}}? 
You should create one access group per Nexudus item you want to connect to {{variable.OpenPath}}. *For example, if you have 3 resources and 4 passes that you'd like to connect to {{variable.OpenPath}}, you'll need 7 access groups.* 