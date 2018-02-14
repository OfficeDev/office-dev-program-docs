---
title: Set up an Office 365 developer subscription
description: 
ms.date: 2/16/2018
---


# Set up an Office 365 developer subscription 

## What is the Microsoft Office 365 Developer Program? 

The Microsoft Office 365 Developer Program provides an Office 365 developer subscription trial as one of its benefits. This trial is ideal for developers who want to test Office 365 features.

This article shows you how to create a one-year Office 365 Enterprise E3 Developer trial with 25 user licenses. While the sign-up process is relatively simple, provisioning all the Office 365 services takes additional time. No payment details are required. 

To sign up, follow the steps in the following sections.

> [!NOTE] 
> If you aren't looking for a trial, you can [buy a Visual Studio subscription](https://www.visualstudio.com/vs/pricing/), which includes an Office 365 Developer subscription for up to 25 users. 

## Join the Office 365 Developer Program

1. Go to the [Join the Office 365 Developer Program](https://aka.ms/devprogram) and select **Join now**.

2. Sign in with your Microsoft account.

3. On the Office 365 Developer Program Signup page, complete the following fields in the online form:
  - First name
  - Last name
  - Contact email
  - Country/region
  - Company

4. Select the **terms and conditions** check box to accept it.

5. Optionally, select the **I would like to hear from the Office 365 Developer Program** check box if you wish to hear from Microsoft about new capabilities and other updates. 

6. Select **Join**.

7. On the Office 365 Developer Program Preferences page, tell us your preferences so we can personalize your experience: 
  - Industry that you work in
  - The type of applications or solutions you're interested in developing
  - Products, technologies, and programming languages that you're interested in

8. When you're finished, select **Save**. Your preferences appear on the next page in the top right, and you receive a Welcome message.

## Set up your trial subscription

1. To get a free nine-month trial, on your profile page, under **Need an Office 365 subscription to use for development?**, select **Sign up**.

2. Provide a user name and a chosen .onmicrosoft.com domain, add a password, select the **terms of use** check box, and then select **Create**. <!--Is this a new user name and password for the subscription that's different from their MSA or Azure AD info? If so, we need more information in the UI about how to fill out these fields, or we can add it to this documentation.-->

3. When the operation finishes, your subscription name and expiration date appear on your profile page. This account becomes the Global Admin for the subscription.

  > [!NOTE] 
  > Don’t forget this username and password, write it down somewhere!

4. Next, a verification step is required to prove you’re not a robot.

<!--I copied the following sections from the wiki page and am not sure what the new experience will be. -->


## Configure the subscription 

1. If not opened automatically, open the setup page.  On the front of the admin page, there should be a **Go to setup** link to bring this up.   

2. The Office 365 Enterprise E3 Developer setup screen appears with three stages; configure these as required. 
  - Personalize sign-in 
  - Add users 
  - Get apps 

3. In the admin portal, in the **Active users** section, assign the Office 365 Enterprise E3 Developer licenses to add users to the account that you created. 

## Provision Office 365 services

This final stage is simply waiting while all the backend services are spun up and provisioned for the tenant, such as SharePoint and Exchange.  This can take some time. During this step, some of the icons in the app launcher and home page are shown as **Setting up (This app is still being set up)** and unavailable until completed. This shouldn’t take much longer than an hour at most to complete.

At the end of this process, the new Office 365 subscription can be used for development and testing. The trial expires after nine months.

A suggested next step is to enable release options, which is ideal for receiving the latest Office 365 features as soon as possible. For more information, see [Set up the Standard or Targeted release options in Office 365](https://support.office.com/en-us/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47?ui=en-US&rs=en-US&ad=US).

Delete your profile

Delete all your events

## Notes 

...from current way of doing things -- not sure if these still apply

- You must use InPrivate browsing to redeem the code. 
- This offer is a developer sandbox offer, and is not compatible with any other offers.  For example, you cannot have a paid E5 offer, Visio offer, and this offer all-in-one. 
- The limit is one subscription of this trial per tenant lifetime; that is, contoso.com can only sign up for this offer once.  You can request another trial tenant to create a second trial with contoso2.onmicrosoft.com. 
- These promo codes may not be used to extend a currently existing offer, paid or otherwise.  As in #3, you must request and create a net new tenant at this time.

### Get started with the Office 365 developer subscription 

- Get a subscription (basically will point to previous topic) 
- Access your Azure subscription (you get this as part of the developer subscription, but not everyone knows how to get to it via the Azure portal) 
- Configure your subscription 
  - Question some topics I've found include getting an Azure subscription. Is this needed? 
  - Add users in Office 365 (this will just be a link out) 
  - Leverage the Office 365 CLI tool to change settings (be clear on the what you can do Follow up with Vesa.) (this is also a link out) 

### Next steps (Choose your journey) (intro to next section) 

- Add Sample data by using the Graph Explorer (need more info) 
- Create app catalog (sharepoint) link to sp topic 
- Create developer site (sharepoint) link to sp topic 
- Add ScriptLab to all clients to the subscription to enable Office add-ins (need more info) 
- Enable Teams Development and Sideloading (need more info) 
- Your O365 subscription IS an Azure subscription. So we need a document that explains how to access it on the Azure portal.

### Documentation requests for Wave 1 (from slide deck)

- Overview of Developer Program​
- Acquire a subscription options  [Dev Subscription | Visual Studio | Paid $99 offer | Microsoft Partner Network Benefits (MPN IUR)]​
- Customize your development subscription for your use.​
- [Add users in Office 365](https://support.office.com/en-us/article/add-users-individually-or-in-bulk-to-office-365-admin-help-1970f7d6-03b5-442f-b385-5880b9c256ec) ​
- [Leverage the Office 365 CLI tool to change settings​](https://dev.office.com/blogs/announcing-office-365-cli-for-managing-your-office-365-subscription-on-any-platform)   to be clear on the what you can do. Follow up with Vesa.​
- Add Sample data by using the Graph Explorer​
- Add ScriptLab to all clients to the subscription to enable Office add-ins​
- Enable Teams Development and Sideloading​
- Need help?​
- Have questions on how to get started building? Dev.office.com/support​
- Subscription issue? ->  FAQ / Trouble shooting guide  ​
- Privacy and terms of use​
- Program terms of use ​
- Dev subscription license agreement [Suzanna]


