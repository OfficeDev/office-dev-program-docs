---
title: Set up an Office 365 developer subscription
description: Set up an Office 365 developer subscription for building and testing solutions independent of your production environment.
ms.date: 03/16/2018
---

# Set up an Office 365 developer subscription 

Set up an Office 365 developer subscription to build and test your solutions independent of your production environment. The subscription is an Office 365 Enterprise E3 Developer subscription with 25 user licenses. It lasts for nine months and is free to use for development purposes (coding and testing solutions).

## Set up your subscription

1. To get an Office 365 developer subscription, on your profile page, under **Need an Office 365 subscription to use for development?**, choose **Sign up**.

2. Create a username and domain. This account will have global administrator permissions for the subscription. You can choose any domain name as long as it is not already in use.

3. Create and confirm a password. Review the **terms of use** check box. You'll need to select the check box before you can continue.

  > [!NOTE]
  > Make a note of your username and password so you don't forget it. 

4. Choose **Create**.

5. After the subscription is created, your subscription name and expiration date appear on your profile page.

<!--I copied the following sections from the wiki page and am not sure what the new experience will be.-->

## Configure the subscription

1. If it doesn't open automatically, open the setup page. On the admin page, choose **Go to setup**.

2. On the Office 365 Enterprise E3 Developer setup screen, configure the three options as required:

  - Personalize sign-in
  - Add users
  - Get apps
  
3. In the admin portal, in the **Active users** section, assign the Office 365 Enterprise E3 Developer licenses to add users to the account that you created.

## Provision Office 365 services

It will take some time for the backend services, such as SharePoint and Exchange, to provision for the subscription. During this step, some of the icons in the app launcher and on the Home page show as **Setting up (This app is still being set up)**. This will take no longer than an hour.

When the provisioning is complete, you can use the new Office 365 subscription for development and testing. The subscription expires after nine months.

We also recommend that you enable release options to ensure that you get access to the latest Office 365 features as soon as possible. For more information, see [Set up the Standard or Targeted release options in Office 365](https://support.office.com/en-us/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47?ui=en-US&rs=en-US&ad=US).

## Add users

For many scenarios, you'll need to test with user accounts with different permissions and settings. You can add up to 25 user accounts with your subscription. To add users, see [Add users individually or in bulk to Office 365 - Admin Help](https://support.office.com/en-us/article/add-users-individually-or-in-bulk-to-office-365-admin-help-1970f7d6-03b5-442f-b385-5880b9c256ec).

## Set up a Microsoft Azure account

For some Office solutions, you might need a Microsoft Azure account to build and test using Azure services. To set up a free Azure account, see [Create your Azure free account today](https://azure.microsoft.com/en-us/free/).

## Leave the developer program

If you decide that you no longer want to participate in the Office 365 Developer Program, you can end your subscription and leave the program.

  > [!WARNING]
  > The following steps will erase all of your profile information. You will lose any data stored in your developer subscription that is not backed up elsewhere.

1. Sign in to the developer program.

2. Choose **Delete Profile**.

3. In the **Delete your profile** confirmation box, choose **Delete**.

## What's in the Office 365 developer subscription

- [Exchange Online (Plan 2)](https://products.office.com/en-us/exchange/compare-microsoft-exchange-online-plans)
- [Flow for Office 365 Plan 2](https://flow.microsoft.com/en-us/pricing/)
- [Microsoft Forms (Plan E5)](https://support.office.com/en-us/article/Frequently-asked-questions-about-Microsoft-Forms-495c4242-6102-40a0-add8-df05ed6af61c?ui=en-US&rs=en-US&ad=US )
- [Microsoft Planner](https://products.office.com/en-us/compare-all-microsoft-office-products?tab=2 )
- [Microsoft Stream for O365 E5 SKU](https://products.office.com/en-us/business/office-365-enterprise-e5-business-software )
- [Microsoft Teams](https://products.office.com/en-us/business/office-365-enterprise-e5-business-software )
- [Mobile Device Management for Office 365](https://support.office.com/en-us/article/Set-up-Mobile-Device-Management-MDM-in-Office-365-dd892318-bc44-4eb1-af00-9db5430be3cd)
- [Office 365 ProPlus](https://products.office.com/en-us/business/office-365-proplus-business-software)
- [PowerApps for Office 365 Plan 2](https://powerapps.microsoft.com/en-us/pricing/ )
- [SharePoint Online for Developer](https://products.office.com/en-us/SharePoint/compare-sharepoint-plans)
- [Skype for Business Online (Plan 2)](https://products.office.com/en-us/skype-for-business/online-meeting-solutions)
- [Sway](https://sway.com/)
- [To-Do (Plan 3)](https://todo.microsoft.com/en-us)



<!-- ## Linda's Notes 

- **Delete all your events** *(need more info here)*

...from current way of doing things -- not sure if these still apply. Also some notes from David's content plan. 
Save what applies, delete what doesn't.

### Info we give out to current customers when we send their promo codes:
- You must use InPrivate browsing to redeem the code. 
- This offer is a developer sandbox offer, and is not compatible with any other offers.  For example, you cannot have a paid E5 offer, Visio offer, and this offer all-in-one. 
- The limit is one subscription per lifetime; that is, contoso.com can only sign up for this offer once.  You can request another subscription to create a second subscription with contoso2.onmicrosoft.com. 
- These promo codes may not be used to extend a currently existing offer, paid or otherwise.  As in #3, you must request and create a net new tenant at this time.

### Get started with the Office 365 developer subscription 

- Get a subscription (basically will point to previous topic) 
- Access your Azure subscription (you get this as part of the developer subscription, but not everyone knows how to get to it via the Azure portal) 
- Configure your subscription 
  - Question: some topics I've found include getting an Azure subscription. Is this needed? 
  - Add users in Office 365 (this will just be a link out) 
  - Leverage the Office 365 CLI tool to change settings (be clear on the what you can do, follow up with Vesa.) (this is also a link out) 

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
- Dev subscription license agreement [Suzanna]-->

## See also

- [Configure your subscription to build Office 365 solutions](configure-your-office-365-developer-subscription.md)
- [Office 365 Developer Program FAQ](office-365-developer-program-faq.md)
