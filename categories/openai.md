## Metadata_Start 
## code: en
## title: OpenAI 
## slug: openai 
## seoTitle: OpenAI 
## description:  
## contentType: Markdown 
## Metadata_End
## What is {{variable.OpenAI}}?
The {{variable.OpenAI}} integration is a conversational model powered by artificial intelligence that can help you automate your {{variable.helpdesk}}.

Every time a {{variable.customer}} sends a {{variable.helpdeskmessage}} via your {{variable.MembersPortal}}, {{variable.OpenAI}} goes through your {{variable.FAQarticles}} and finds the best answer. You can think of it as your own support agent, ready to answer customer queries in a matter of seconds any day, any time. 

![OpenAI_LiveHelpRequest](https://cdn.document360.io/4f9a66c7-3dbb-4052-97d8-5439302e1512/Images/Documentation/OpenAI_LiveHelpRequest.gif){height="" width=""}

If {{variable.OpenAI}} cannot find an answer in your  {{variable.FAQarticles}}, the relevant department manager receives a notification to manually tackle the request, as they usually would. 
* * *


## How to integrate {{variable.OpenAI}} 
Integrating {{variable.OpenAI}} is a  three-process: 

**1. Create an API key in {{variable.OpenAI}}.**
**2. Enable {{variable.OpenAI}} {{variable.OnTheAdminPanel}}.**
**3. Test {{variable.OpenAI}}'s answers before going live.**

All you need to get started is a paying {{variable.OpenAI}} account and some {{variable.FAQarticles}} in {{variable.Nexudus}}. From there, you enable the integration {{variable.OnTheAdminPanel}} and test the answers customers will get from {{variable.OpenAI}}. Once you're happy with the way {{variable.OpenAI}} answers questions, you can go ahead and enable it for your {{variable.helpdesk}}. 

{{variable.MoreInformation}} [Integrating OpenAI](/v3/docs/integrating-openai){target="_blank"}. 

{{snippet.OpenAILimitations_Warning}}


:::(Internal) (Private notes)
**Prompt max tokens** - 1024
**Temperature** - 0
:::
* * *

## FAQ 


### Is  {{variable.OpenAI}} free to use? 
No, each help-desk request sent by a {{variable.customer}} is charged according to the {{variable.OpenAI}} token-based pricing for **Davinci (text-davinci-003)** available at [openai.com/pricing](https://openai.com/pricing){target="_blank"}. 

### How will  {{variable.OpenAI}}  charge me? 
{{variable.OpenAI}} charges you per token. Each message a {{variable.customer}} sends through your {{variable.helpdesk}} uses multiple tokens. The number of tokens used per request varies based on the length of the questions asked. 

How much {{variable.OpenAI}} will charge you varies based on the number of messages your {{variable.customers}} send and how long each message is. More information on pricing for **Davinci (text-davinci-003)** is available at [openai.com/pricing](https://openai.com/pricing){target="_blank"}. You can also cap the amount {{variable.OpenAI}} can charge you every month at [platform.openai.com/account/billing/limits](https://platform.openai.com/account/billing/limits){target="_blank"}. 

### Where can I find my  {{variable.OpenAI}} API key? 
{{snippet.OpenAI_APIKey}}. 

### Does {{variable.OpenAI}} work in multiple languages? 
Yes, {{variable.OpenAI}} can work in most languages. *For example, you can ask a question in Spanish and get an answer in Spanish, even if your {{variable.FAQarticles}} are in English.* 

