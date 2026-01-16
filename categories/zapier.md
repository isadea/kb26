## Metadata_Start 
## code: en
## title: Zapier 
## slug: zapier 
## seoTitle: Zapier 
## description: Automate your operations with Zapier and Nexudus. Connect platforms, create Zaps, and streamline tasks effortlessly for better efficiency. 
## contentType: Markdown 
## Metadata_End
## What is {{variable.Zapier}}? 
{{variable.Zapier}} is an automation tool that lets you connect {{variable.Nexudus}} to hundreds of other platforms to automate part of your operations. 

*For example, whenever a new customer joins your space, add them to one of your newsletter grousp in Mailchimp.* 

## How the {{variable.Zapier}} integration works
You just need a {{variable.Zapier}} account to get started. If you don't have a {{variable.Zapier}} account yet, you can create one in a few clicks via their [signup form](https://zapier.com/sign-up/){target="_blank"}. 

:::(warning) (Make sure your [{{variable.Zapier}} license](https://zapier.com/pricing){target="_blank"} matches the number of {{variable.Zaps}} you want to create and the number of tasks you  trigger each month.)
:::
Once you have your account with the adequate license, you can connect {{variable.Zapier}} to Nexudus and start building your {{variable.Zaps}} in a matter of minutes. 

{{variable.MoreInformation}} [Integrating {{variable.Zapier}}](/v3/docs/integrating-zapier){target="_blank"}.

* * *

## Instant vs Polling triggers 

{{variable.Nexudus}} offers two types of triggers in {{variable.Zapier}}: **instant** and **polling**. 

### Instant triggers
Instant triggers automatically send the relevant data to {{variable.Zapier}} as a record is created, updated or deleted in Nexudus. Data is transfered from Nexudus to another platform in real-time. All instant triggers are labelled in the **Trigger event** drop-down list.

:::(Info) (Instant triggers are the best option for most {{variable.Zaps}}.)
We recommend using instant triggers over polling ones if both are available for the same action.
:::
 
### Polling triggers
Polling triggers automatically send the relevant record data when {{variable.Zapier}} requests it. {{variable.Zapier}} requests record data at set intervals based on your {{variable.Zapier}} plan. Intervals usually range from **2 to 15 minutes**. Nexudus can return up to 250 records per Zapier  data request. 

:::(Warning) (Do not use polling triggers if you create, edit, or delete more than 250 records per polling interval as data above the threshold won't reach {{variable.Zapier}}.)
:::

You can also filter your {{variable.Zaps}} using most of the fields in a record for both instant and polling triggers. 

*For example, you want to trigger a {{variable.Zap}} when an article is published, but only if the article is in the **New Releases** category.*

* * *
## FAQ

### Why can't I find {{variable.Nexudus}} on {{variable.Zapier}}? 
Our integration with {{variable.Zapier}} is invite-only, which means that you cannot search for it directly in {{variable.Zapier}}. You need to [connect the integration {{variable.OnTheAdminPanel}}](/docs/integrating-zapier){target=`_blank`} before being able to create Zaps.

### Can I connect {{variable.Nexudus}} to any platform through {{variable.Zapier}}? 
Any platform that's available in {{variable.Zapier}} can be connected to Nexudus. Some limitations will apply based on the Zap you're trying to build and the data needed from Nexudus to build the {{variable.Zap}}.

### Can you help me with my Zaps? 
We're working in tutorials for common Zaps. In the meantime, if you need extra help on your Zaps, you can always get in touch with us at {{variable.SupportEmail}}. 