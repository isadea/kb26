## Metadata_Start 
## code: en
## title: Genetec 
## slug: genetec 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## 
## What is Genetec?

Genetec is an access control system that lets your customers unlock doors autonomously based on their purchases using access cards. 

![Genetec_Image.jpg](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/Genetec_Image.jpg){height="400" width=""}


:::(Warning) (Using the {{variable.Genetec}} integration adds a **$/£/€50 monthly charge** to your Nexudus subscription per location enabled.)
:::


## How the Genetec Integration Works

You define access groups in Genetec for each pass, resource, desk, and office you have set up in your Nexudus inventory. You can then enable the integration in Nexudus and connect the access groups to the corresponding Nexudus items.

Once the integration is enabled in Nexudus, your customers can start unlocking doors using access cards. The doors they can unlock are defined by the access groups they've been added to based on their purchases, bookings, and contracts.

{{variable.MoreInformation}} [Integrating Genetec](/v3/docs/integrating-genetec){target="_blank"}.

## Access Card Requirements
Nexudus currently supports the automatic creation and update of **HID Corporate 1000 35 Bits** cards. These cards have two components: a **facility code** and a **card number**.  Use the **Access fob** field to store the facility code in Nexudus.

:::(Internal) (Private notes)
Do we need to support more?  There are 9 different types of cards, each with a varying number of parameters: -

![image.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/image%28567%29.png){height="" width=""}

https://techdocs.genetec.com/r/en-US/Security-Center-Administrator-Guide-5.10/Assigning-credentials
:::