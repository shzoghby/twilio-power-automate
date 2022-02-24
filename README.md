# Twilio Power Automate Flows

## Overview
[Microsoft Dynamics 365](https://dynamics.microsoft.com) is a line of enterprise resource planning and customer relationship management software applications. In this project, we will have the [Power Automate](https://powerapps.microsoft.com) flows that you can trigger using HTTP or Dataverse to quickly send SMS notifications to:
1. Contact Entity
2. Static/Dynamic Marketing List Members
3. all members in all Static/Dynamic Marketing Lists of a selected Campaign

---

## Prerequisites
First, you need to set up your Twilio account, Microsoft account, Dynamics account and purchase a Twilio phone number.

- If you haven't yet, [sign up for a free Twilio Account](http://www.twilio.com/referral/AaAiEA).
- [Purchase a phone number](https://support.twilio.com/hc/en-us/articles/223135247-How-to-Search-for-and-Buy-a-Twilio-Phone-Number-from-Console) from the Twilio Console, if you don't yet have one (you'll need one with SMS capability).
- Create a [Microsoft Account](https://account.microsoft.com/account), if you don't yet have one.
- [Sign up for a Dynamics 365 Customer Service free trial](https://account.microsoft.com/account), if you don't yet have one.

```
Note: For production 'Dynamics 365 Sales Premium', 'Dynamics 365 Sales Enterprise', or 'Dynamics 365 Sales Professional' license will be needed to use HTTP triggers and Microsoft Dataverse connectors in Power Automate.
```

---

## Flows Setup & Configurations

### HTTP Triggered Flows
#### Import the flow
Here are the steps to import your flow:
1. Go to https://australia.flow.microsoft.com and login using your Microsoft Account.
1. Click on the import button in the top right hand corner of the screen.
1. Upload the package file from here and wait for the screen to show up the package details.
1. When configuring the flow settings, you can choose to either create a new flow or update an existing one with the flow definition from the package.
1. You will also need to select the connections that are required to setup the flow as part of the import process. You should see the Import button light up once you have successfully configured all the required settings.
1. Click on Import and wait for the process to be completed.

#### Configure the flow
1. Here are the steps to configure your flow:
1. Click on My flows, then find your flow.
1. Click on the three dots beside your flow, then click on Edit.
1. Expand Initialize variable - varSMSSendFromNumber and set the value to <your-purchased-twilio-number>.
1. Expand When a HTTP request is received trigger and copy the HTTP POST URL 
1. Click on Back arrow, then click on Turn on to enable your new flow.

### Dataverse Triggered Flows
*content to add later*

---

