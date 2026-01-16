## Metadata_Start 
## code: en
## title: Webhooks 
## slug: webhooks 
## seoTitle: Webhooks 
## description:  
## contentType: Markdown 
## Metadata_End
## What are webhooks?

{{variable.Nexudus}} webhooks can automatically push data to other systems when a specific action takes place in {{variable.Nexudus}}. The receiving end of these webhooks should be a system that understands this type of data and can process it.

The receiving end of a webhook listens for incoming calls coming from {{variable.Nexudus}} with specific data. 

*For example, if you want to notify another system every time you make a change to a member or contact you could use the **Customer Update** webhook, which sends the data of the contact or member whose record you have updated.*

## How webhooks work 

You can create webhooks in a few clicks {{variable.OnTheAdminPanel}}. Webhooks are created by clicking Settings > Integrations > Webhooks on the Admin Panel. 


## Available webhooks list
The webhooks listed below are the ones we currently have available. We keep expanding this list based on user requests.

### Access control 

* Updated

* * *

### {{variable.ArticlesCAP}}

* Created 
* Updated 
* Deleted

* * *

### {{variable.Bookings_CAP}}
* Created 
* Updated 
* Deleted


* * *

### Chat message
* Created 

* * *

### Check-in 

* Attempt failed 
* Updated
* Deleted

* * *
### Community groups (also known as [discussion board groups](/docs/managing-discussion-board-groups){target=`_blank`}) 


***

### Community messages ( also known as [discussion boards](/docs/discussion-boards){target=`_blank`})

* Message created
* Thread created

* * *

### {{variable.Contracts_CAP}} 
* Created
* Activated 
* Cancelled
* First activated 
* Renewed 
* Updated
* Upgraded/downgraded


* * *

### Credit notes 

* Created

* * *

### {{variable.Customers_CAP}}

* Failed check-in
* Check-in
* Check-out
* Created 
* Updated 
* Deleted 
* Welcome Email sent


#### {{variable.Customer_Field}} message
* Created 


#### {{variable.Customer_Field}} {{variable.Products_CAP}} 
* Created 
* Updated 
* Deleted

* * *

### Deliveries 

* Created
* Assigned to {{variable.customers}}

* * *

### {{variable.EventAttendees_CAP}}

* Created 
* Updated
* Deleted

* * *

### {{variable.Events_CAP}}

* Created
* Updated
* Deleted

***
### Floor plans 
* Created 
* Updated
* Deleted 
* * *
### Floor plan desks

* Created
* Updated
* Deleted


* * *

### Help-desk 

* Message created
* Reply created 


* * *
### {{variable.Invoices_CAP}}

* First created 
* Created 
* Updated
* Cancelled / refunded 
* Deleted 
* Awaiting payment 
* Received payment
* Failed payment 
* Fully paid 

* * *
### Newsletter {{variable.subscribers}}

* Created
* Subscribed 
* Unsubscribed 
* Removed from group

***
## Payment methods 
* Created 
* Updated
* Deleted 

* * *
### {{variable.Plans_CAP}}

* Created 
* Updated
* Deleted 


* * *
### Products
* Created 
* Updated
* Deleted 
***

### {{variable.Proposals_CAP}} 
* Created 
* Updated
* Cancelled/refunded 
* Deleted 

For more information on the specific fields and properties included in the webhooks, check out [our API documentation](https://developers.nexudus.com/reference/proposal).

* * *
### Space (also known as a location)
* Updated
***

### {{variable.Teams_CAP}}

* Created 
* Updated
* Deleted 


* * *

### {{variable.VisitorsCAP}}
* Created
* Checked-in
* Notified
* Deleted

Webhook requests created by our servers can be verified by calculating a digital signature using a shared secret you can type from the webhooks integration.

## GET Webhook Types

```
GET https://spaces.nexudus.com/api/utils/enums?name=eWebhookAction
```

