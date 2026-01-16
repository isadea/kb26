## Metadata_Start 
## code: en
## title: Slack 
## slug: slack 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## What is {{variable.Slack}}?
{{variable.Slack}} is a messaging app for businesses. Our integration lets you do the following: 

* **Push Events and Articles Notifications to {{variable.Slack}}** 
* **Send Invoice Notifications through {{variable.Slack}}**
* **Send Messages to Customers through {{variable.Slack}}**
* **Send Admin Notifications through {{variable.Slack}}**


## How the {{variable.Slack}} Integration Works
The {{variable.Slack}} integration works by installing a private app in your {{variable.Slack}} account and then enabling the integrations on the {{variable.AdminPanel}}. 

:::(Warning) (You must **manually** invite all the relevant admins and customers to your {{variable.Slack}} workspace using the same email address they have on record in Nexudus.)
Nexudus currently cannot automatically sync users from Nexudus to {{variable.Slack}}.
:::
### Pushing Events and Article Notifications
Once the integration is enabled, you can push a notification by clicking the ellipsis icon next to any event or blog article you want to share in Slack. 

![image.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/image%28665%29.png){height="" width="500"}
 
 The notifications are pushed to the Slack channel you defined as the **Public announcement channel** on the {{variable.AdminPanel}}. The notification includes a link to the event or article page on your {{variable.MembersPortal}}. 
 
### Pushing Customer Messages
Once the integration is enabled, customers will receive private messages in {{variable.Slack}} whenever you send them from the Admin Panel to their inbox and in {{variable.Slack}} automatically. 

![image.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/image%28666%29.png){height="" width="500"}

### Automated Invoice Notifications for Customers
Once the integration is enabled, customers will receive a private notification in Slack every time they receive an invoice notification via email.

![image.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/image%28672%29.png){height="" width="500"}

### Automated Admin Notifications
Once the integration is enabled, admins will receive a private notification in Slack every time Nexudus sends them an admin notification via email based on their notification preferences. 

![image.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/image%28671%29.png){height="" width="500"}

{{variable.MoreInformation}} [Managing Admin Notifications](/v3/docs/admin-notifications){target="_blank"}.



* * *
## FAQ
### Are notifications and messages still sent to customers and admins via email?
Yes, customers and admins will receive notifications through {{variable.Slack}} on top of the corresponding email notifications they usually get from from your space. 

### Can I send other notifications such as reminders through this integration? 
No, you can only push events and article notification to customers in {{variable.Slack}}. Admins automatically receive {{variable.Slack}} notifications based on their [notification preferences](/v3/docs/admin-notifications){target="_blank"} in Nexudus. 

### Are my customers automatically added to my {{variable.Slack}} workspace? 
No, you'll need to manually invite all your customers and admins in Nexudus to the relevant workspace in {{variable.Slack}}. 
