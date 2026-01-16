## Metadata_Start 
## code: en
## title: Verifalia 
## slug: verifalia 
## seoTitle:  
## description:  
## contentType: Markdown 
## Metadata_End
## 
## What is {{variable.Verifalia}}?
Verifalia is a real-time email validation service that verifies the email addresses provided by customers. {{variable.Verifalia}} checks the validity and safety of each email address without ever getting in touch with your customers. 

For more information about the features available and detailed pricing, visit [Verifalia's website](https://verifalia.com/){target="_blank"}.

## How the {{variable.Verifalia}} Integration Works

Once you have a {{variable.Verifalia}} account and enable the integration in Nexudus, the email addresses provided by customers being registered from the Admin Panel or via the signup form of the Members portal are automatically verified. 

If their email address isn't valid, Nexudus won't allow the new customer to be created or the email address change to be saved. Every verification automatically generates an individual verification report in Verifalia. 

:::(Warning) (Admin email addresses are never verified.)

:::
### Verification Levels  
You need to select a **Verification level** when you enable the integration. This level defines the email addresses Nexudus will accept based on their status in Verifalia.

![Verifalia_VerificationLevel.png](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/Verifalia_VerificationLevel.png){height="" width=""}

You can choose from two verification levels: flexible or strict. You can compare the two levels below based on which Verifalia email classes they automatically allow and reject. 
<div class="flex-container" style="display: flex; flex-wrap: wrap; width: 100%; align-items: start;">
  <div class="column" style="width: 50%; padding:30px;">
   <h3>Flexible </h3>
      <h4 style="color: #29a700;">Allowed</h4> 
       <li><b>Deliverable</b> - the email exists and can receive new messages.</li>
        <li><b>Risky</b> - the email exists but its safety is not guaranteed.</li>
       <h4 style="color: red;">Rejected</h4> 
       <li><b>Undeliverable</b> - the email doesn't exist or can't receive new messages.</li>
       <li><b>Unknown</b> - the email returned an unknown error.</li>
    </div>
  <div  class="column" style="width: 50%; padding:30px;">
       <h3>Strict</h3>
<h4 style="color: #29a700;">Allowed</h4> 
      <li><b>Deliverable</b> - the email exists and can receive new messages.</li>
      <h4 style="color: red;">Rejected</h4> 
      <li><b>Risky</b> - the email exists but its safety is not guaranteed.</li>
      <li><b>Undeliverable</b> - the email doesn't exist or can't receive new messages.</li>
       <li><b>Unknown</b> - the email returned an unknown error.</li>
    </div>
</div>

:::(Warning) (Customer **billing email addresses** are not verified.)
:::
If the email address falls into a rejected {{variable.Verifalia}} class, you won't be able to create or update the customer and receive an error message. 


