---
title: Set up a Microsoft 365 developer sandbox subscription
description: Set up a Microsoft 365 developer subscription for building solutions independent of your production environment.
ms.date: 04/01/2019
ms.localizationpriority: high
---

# Set up a Microsoft 365 developer sandbox subscription 

Set up a Microsoft 365 developer sandbox to build your solutions independent of your production environment. Your developer program membership, which you join as a regular member or through Visual Studio enterprise, includes a Microsoft 365 E5 developer sandbox subscription with 25 user licenses. It lasts for 90 days and is free to use for development purposes (coding solutions) only. Commercial transactions, including purchasing paid services, are not supported.

> [!NOTE] 
> To set up a subscription, you must first [join the Microsoft 365 Developer Program](microsoft-365-developer-program.md) directly or through Visual Studio Professional or Enterprise (if you're a subscriber). After joining, you'll see the option to set up a subscription.

You can choose to set up either an instant sandbox or a configurable sandbox.

## Instant sandbox

If you choose an instant sandbox, you can cut your sandbox configuration time from days to seconds. The Microsoft 365 instant sandbox comes pre-provisioned with Microsoft Teams, SharePoint, Outlook, and Office. It also includes licenses for 24 test users plus one admin, and the latest Microsoft 365 apps for your PC and Mac, including Power Apps, Power BI, Enterprise Mobility + Security, Office 365 Advanced Threat Protection, and Microsoft Entra ID.

In addition, you get pre-installed sample data, including the new Teams sample data pack, as well as Microsoft Graph user, mail, and calendar data and SharePoint Framework sample data, which simulate a small corporate environment to help you build solutions across the Microsoft 365 platform. For details, see [Developer sandbox sample data](install-sample-packs.md).

> [!VIDEO https://www.microsoft.com/en-us/videoplayer/embed/RWOmCY]

You cannot customize your domain name if you choose this option.

## Configurable sandbox

If you choose a configurable sandbox, you can customize your domain name. You will have an empty sandbox that you must populate with sample data. This sandbox can take up to two days to provision. You can choose to install the sample data packs one by one that are available on your developer program dashboard. For details, see Developer sandbox sample data.

## Set up your Microsoft 365 E5 sandbox subscription

To get a Microsoft 365 developer subscription:

1. On your profile page, choose **Set up E5 subscription**.

2. In the **Set up your Microsoft 365 E5 developer subscription** dialog box, choose whether you want an instant sandbox or a configurable sandbox, and then choose **Next**.

If you selected an instant sandbox:

1.	Choose the **Country/region for your data center**, and provide an **Admin username** and **Admin password**, and optionally an alternative password for your fictitious users, and then choose **Continue**.

    > [!IMPORTANT] 
    > Make a note of your username and password because you'll need it to access your developer subscription.

2. If you're a Visual Studio subscriber, on the **Link with Visual Studio** dialog box, select an option from the dropdown menu, and choose **Continue**. Otherwise, continue to step 3.

3.	Provide a valid cell phone number and choose **Send code**. Enter the code that you receive, and then choose **Set up**.

    > [!NOTE] 
    > You must use a valid cell phone number and not Voice over IP (VoIP). You can only have one Microsoft 365 Developer Program account associated with your phone number. 

4.	After the subscription is created, your subscription domain name and expiration date appear on your profile page.

If you selected a configurable sandbox:

1.	Choose your **Country/region**, and then provide a username in the **Create username** field and a domain name in the **Create domain field**. Create and confirm your password, and then choose **Continue**.

    > [!IMPORTANT] 
    > Make a note of your username and password because you'll need it to access your developer subscription.

2. If you're a Visual Studio subscriber, on the **Link with Visual Studio** dialog box, select an option from the dropdown menu, and choose **Continue**. Otherwise, continue to step 3.

3.	Provide a valid cell phone number and choose **Send code**. Enter the code that you receive, and then choose **Set up**.

    > [!NOTE] 
    > You must use a valid cell phone number and not Voice over IP (VoIP). You can only have one Microsoft 365 Developer Program account associated with your phone number. 

4.	After the subscription is created, your subscription domain name and expiration date appear on your profile page.


## Configure the subscription

1. On your profile page, choose **Go to subscription** and sign in with your user ID (for example, username@domain.onmicrosoft.com) and the password that you specified for your developer subscription.

   > [!NOTE] 
   > Do not sign in to your subscription with your Developer Program account ID.

2. Use the app launcher to go to the [Admin center](https://admin.microsoft.com/AdminPortal/Home#/homepage).

3. On the Admin center home page, choose **Go to guided setup**. This takes you to the **Microsoft 365 E5 Developer Setup** page.

4. **Install your Office apps**. You have the option of installing Office apps to your computer. When ready, choose **Continue**.

5. **Personalize your sign-in and email**. You can connect your subscription to a domain, or just use the existing subdomain that you created. When ready, choose **Use this domain**, or choose **Do this later**.

6. **Add new users**. You can add fictitious or real users to help you with development. When ready, choose **Add users and assign licenses**.
    
    > [!NOTE]
    > If you have a configurable subscription, after you set up your subscription, you can install the Users sample data pack. The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each. For details, see [Developer sandbox sample data](install-sample-packs.md).

6. **Assign licenses to unlicensed users**. For any users that you want to be able to work with the subscription, grant them a license. When ready, choose **Add users and assign licenses** or **Do this later**.

7. **Share sign-in credentials**. For any real users that will access the subscription, you must share their sign-in credentials with them. You can choose a method, such as email, download, or print. When ready, choose **Continue**.

   > [!TIP] 
   > On subsequent visits to your dashboard, sign in with your *username@domain*.onmicrosoft.com account before you go to the Dashboard.

8. Choose whether you want to send an email to users about Microsoft Teams, and then choose **Continue**.

9. **You've reached the end of setup**. You've completed the setup for your subscription. You can optionally rate the experience. When ready, choose **Go to the Admin center**.
    
   > [!NOTE] 
   > At this time, the subscription's region defaults to North America regardless of which country/region you are in. You can still proceed with setting up and using your developer subscription.

## Set up multifactor authentication

Set up multifactor authentication to safeguard your access to your sandbox. To set up multifactor authentication, sign in to your new sandbox with your admin account. In the left pane, choose **Admin**, choose **Setup**, and then choose **Configure multifcator authentication (MFA)**. Link the MFA to the email and phone number you used when you set up your sandbox. You will be able to use them to recover your sandbox if you forget your password.

## Provision Microsoft 365 services in your configurable sandbox

If you have a configurable sandbox, it will take some time for the backend services, such as SharePoint and Exchange, to provision for the subscription. During this step, some of the icons in the app launcher and on the Home page show as **Setting up (This app is still being set up)**. This will take no longer than an hour.

When the provisioning is complete, you can use the new Microsoft 365 subscription for development. The subscription expires after 90 days. To extend it, see [When my subscription is about to expire, can I extend it?](microsoft-365-developer-program-faq.yml#renew-subscription).

We also recommend that you enable release options to ensure that you get access to the latest Microsoft 365 features as soon as possible. For more information, see [Set up the Standard or Targeted release options](https://support.office.com/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47).

## Set up a Microsoft Azure account

For some Office solutions, you might need a Microsoft Azure account to build using Azure services. This is not included with the Microsoft 365 Developer subscription. To set up a free Azure account, see [Create your Azure free account today](https://azure.microsoft.com/free/).

## Install sample data packs

You can install sample data packs on your configurable sandbox. If you chose the instant sandbox, the sample date packs come pre-installed.

Sample data packs save you time by automatically installing data and content you need to build and test your solutions. This includes fictitious users, metadata, and photos to simulate a small corporate environment. For details about the sample data packs that are available and how to install them, see [Developer sandbox sample data](install-sample-packs.md).

## Set up a development environment and deployment pipeline

For resources to help you set up your development environment and deployment pipeline, engage with the [Microsoft 365 and Power Platform Community](https://pnp.github.io/).

## See also

- [Use your subscription to build Microsoft 365 solutions](build-microsoft-365-solutions.md)
- [Renew an expiring subscription](subscription-expiration-and-renewal.md)
- [Microsoft 365 Developer Program FAQ](microsoft-365-developer-program-faq.yml)
