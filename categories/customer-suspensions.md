## Metadata_Start 
## code: en
## title: Customer Suspension 
## slug: customer-suspensions 
## seoTitle: Customer Suspension 
## description:  
## contentType: Markdown 
## Metadata_End
## What is {{variable.customer}} suspension? 

Customer suspensions temporarily restrict the access and privileges {{variable.customers}} have {{variable.OnTheAdminPanel}} and the {{variable.MembersPortal}}.

Suspended {{variable.customers}} are: 

*  **No longer considered [active users](/v3/docs/who-is-considered-an-active-user-in-nexudus){target="_blank"} in {{variable.Nexudus}}.**
*  **No longer invoiced for their active {{variable.contracts}}.**
*  **Only able to use the {{variable.MembersPortal}} to pay their due {{variable.invoices}}.**

:::(Info) (Suspensions don't revoke {{variable.MembersPortal}} access.)
Suspended {{variable.customers}} retain access to your {{variable.MembersPortal}} unless you also [revoke](/v3/docs/revoking-members-portal-access-to-customers){target="_blank"} their access or [archive](/docs/archiving-customers) their account.
:::

## How customer suspension works 

You can suspend {{variable.customers}} **manually** or **automatically** {{variable.OnTheAdminPanel}}.

### Manual suspension

You can manually suspend a {{variable.customer}} from the {{variable.customer}} record. This is great for when you need to investigate complex or ad-hoc issues with an account. 

*For example, if a {{variable.customer}} has invoicing issues, you can manually suspend their account while you investigate. The suspension will prevent further {{variable.invoices}} until the issue is resolved.*

You can manually suspend {{variable.customers}} at any time, which offers more flexibility than automatic suspensions.

{{variable.MoreInformation}} [suspending customers](/docs/suspending-customer-accounts){target=`_blank`}.

### Automatic suspension

You can also automatically suspend {{variable.customers}} through signup settings and CRM boards when:

* A new {{variable.customer}} joins your {{variable.space}}
* A {{variable.customer}} opts for a new {{variable.plan}} 
* A {{variable.customer}} is added as an {{variable.opportunity}} to a {{variable.CRMboard}}

*For example, automatically suspend new {{variable.customer}} accounts until all identity checks are complete to enhance the security of your signup process.*

Automatic suspensions help you suspend customers when they meet certain conditions. They can help you streamline processes such as onboarding and offboarding,

{{variable.MoreInformation}} [suspending customers](/docs/suspending-customer-accounts){target=`_blank`}.

:::(warning) (You'll need to manually [lift the suspension](/v3/docs/activating-customer-accounts){target="_blank"} for {{variable.customers}} to regain full access to your {{variable.MembersPortal}}.)
This applies to {{variable.customers}} you manually suspend on the {{variable.AdminPanel}} and {{variable.customers}} who are automatically suspended via CRM boards and signup settings.
:::


 