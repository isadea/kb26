## Metadata_Start 
## code: en
## title: Validation Rules 
## slug: validation-rules 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## 
## What are validation rules? 
Validation rules are records checks that help you prevent customers and admins from creating or editing a record if a condition isn't met. 

*For example, you want to make sure **all** customers have a **VAT number** on record. Another example would be preventing customers from booking a resource if they didn't purchase a specific product.*

You can set up validation rules for the following record types: 

{{snippet.ValidationRules_RecordsList}}

:::(Warning) (Validation rules apply to records your create or update on the **{{variable.AdminPanel}}**, the **{{variable.MembersPortal}}**, the [**Nexudus companion apps**](https://help.nexudus.com//v3/docs/apps){target="_blank"}, the [Imports](/v3/docs/data-imports){target="_blank"} page, and the **API**.)
:::
:::(Info) (Validation rules you create in a **Network** location automatically apply to all other locations within the network.)
:::

## How validation rules work 

Validation rules rely on a formula that assesses if a condition you define is met before creating or updating a record. The formula is simply what you tell Nexudus to check whenever a customer or an admin tries to edit a record. 


## Validation rule templates

We currently offer the following validation rules templates to create common validation rules in a few clicks.

![VR_WizardsExample.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/VR_WizardsExample.png){height="500" width=""}

### Make VAT Number Required
This validation rule can make the VAT number a required for any customer.

### Validate VAT number format
This validation rules prevents customers and admins from adding a VAT number that doesn't match the standard British VAT number format.

### Prevent last minute purchases
This validation rule prevents customers from purchasing products linked to a booking less than 24 hours before the start of the booking.

### Fixed booking times
This validation rule only lets customers start/end bookings at the start of an hour or 30 minutes past the hour.

### Make customer emails unique
This validation rule prevents the registration of any new customer if their email address is already used by another account in Nexudus.

### Require first and last name
This validation ensures customers have at least two words in their full name.

### Prevent multiple contracts
This validation ensures customers only have one active contract.

### Check for full admin role
This validation ensures only users with a full admin role can create or change contracts.

