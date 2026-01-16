## Metadata_Start 
## code: en
## title: PaperCut 
## slug: papercut 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
:::(Warning) (We currently only integrate with {{variable.PaperCut_SupportedVersions}}.)
:::
## What is {{variable.Papercut}}? 
Our integration with [{{variable.Papercut}}](https://www.papercut.com/){target=`_blank`} lets you track printing and charge it through {{variable.Nexudus}}. This includes: 

* **Charging for prints and invoicing them**
* **Giving printing credits that {{variable.customers}} can then use to print through {{variable.Papercut}}**
* **Manage free printing if you offer it**


![PaperCut_Marketing](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/PaperCut_Marketing.png){height="" width=""}


## How the {{variable.Papercut}} integration works

You first need to **[purchase a {{variable.Papercut}} license](https://www.papercut.com/){target=`_blank`}** and **set up your printers**. 

Nexudus currently only intregrates with {{variable.PaperCut_SupportedVersions}}. 

The number of users to include in your {{variable.Papercut}} license depends on the number of {{variable.customers}} you have in each {{variable.location}} that'll use {{variable.Papercut}}. 

*For example, if you have 200 {{variable.customers}} in a {{variable.Nexudus}} {{variable.location}} and you want them all to print using {{variable.Papercut}}, your {{variable.Papercut}} license must include at least 200 users.* 


Once you have a license and your printers set up in {{variable.Papercut}}, you can [start the integration process](/docs/integrating-papercut){target=`_blank`}.

:::(Info) (You need a laptop or desktop running **Windows** or **Linux** complete and manage the {{variable.Papercut}} integration.)
:::

The integration can automatically add new {{variable.customers}} to {{variable.Papercut}} and charges them based on their printing using credits, pay-per-print or a combination of both. You can also choose to let your {{variable.customers}} print for free. 


* * *
## FAQ

### Can I use this integration with {{variable.Papercut}} Hive? 
No, our integration currently works with {{variable.PaperCut_SupportedVersions}}.

### Can I use any printer with this integration?
Our integration works with any printer that [{{variable.Papercut}} MF or NG supports](https://www.papercut.com/products/mf/supported-devices/){target=`_blank`}. If your printers aren't supported by {{variable.Papercut}} MF or NG, it won't work with our integration.

### How often does the extender sync with {{variable.Papercut}}? 
The {{variable.Nexudus}} extender automatically syncs with {{variable.Papercut}} every 15 minutes. This means that any new {{variable.customer}} with printing access in {{variable.Nexudus}} can take up to 15 minutes to sync in {{variable.Papercut}}. If new {{variable.customers}} need to print straight away, you can always trigger a [manual sync](https://help.nexudus.com/v3/docs/transferring-users-to-papercut){target=`_blank`}. 

### How long do you keep my {{variable.Papercut}} logs?
We keep logs of all syncs recorded in {{variable.Papercut}} in the last 30 days. We automatically delete any logs older than 30 days.