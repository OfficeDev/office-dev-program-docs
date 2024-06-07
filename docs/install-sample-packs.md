---
title: Use sample data packs with your Microsoft 365 Developer Program subscription
description: Learn how to install sample data packs on your developer subscription to help get your sandbox environment up and running quickly. 
ms.localizationpriority: high
---

# Use sample data packs with your Microsoft 365 Developer Program subscription

Your Microsoft 365 Developer Program sandbox subscription comes with sample data to save you time by providing data and content you need to build and test your solutions.

## Sample data installed on the instant sandbox

If you have an instant sandbox, the sample data packs are already pre-installed. Your instant sandbox includes the following sample data:

- **Microsoft Graph user, mail, and calendar data** - 16 sample users with user data and content to help you model your solutions. This includes user mailboxes, calendar events, and integration into a Teams developer environment with simulated chats and team memberships.
- **Teams sample data** pack with the following customized developer environment:
  - **App sideloading** pre-configured
  - **Five sample teams, channels, tabs, and chat sessions** built around the 16 sample users.
  - **App Studio / Teams Developer Portal pre-installed and pinned** to help you streamline the creation of your Teams app manifest and app package, plus the card editor and a React control library.
    
    ![Screenshot of the Teams Developer Portal](images/teams-developer-portal.PNG)

## Install sample data packs in your configurable sandbox

If you have a configurable sandbox, you can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.

> [!NOTE] 
> You can't install sample data packs on any other Microsoft 365 subscription. These sample data packs are only compatible with the Microsoft 365 developer sandbox subscription you get as part of the Microsoft 365 Developer Program.

You can find sample data packs on your [Microsoft 365 Developer Program dashboard](https://developer.microsoft.com/en-us/microsoft-365/profile), at the bottom of your subscription tile.

The following sample data packs are currently available:

- Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user. Use Microsoft Graph APIs to work with user sample data in the following ways:
  - Get specific user details
  - Update user
  - Get direct reports
  - Prepare organization chart  
  - Get users by department

- Mail & events - Adds Outlook email conversations and calendar events for each of the 16 sample users. Use Microsoft Graph APIs to work with mail and events sample data in the following ways:
  - Get emails by users
  - Get emails filtered by date
  - Get upcoming events
  - Update/delete upcoming events

  > [!NOTE]
  > You must install the Users sample data pack before you install Mail and Events.
    
### Install the Users sample data pack

Before you install the Users sample data pack, make sure that you have a Microsoft 365 developer subscription and that you assign a license to yourself as the admin.

> [!NOTE]
> Make sure that you have 16 users available in your subscription. Your subscription includes 25 users. If you have already configured more than 10 users, remove some users first to ensure that your installation is successful.

To install the Users sample data pack:

1. Select the **Users** box at the bottom of your subscription tile.
2. Copy your administrator ID; you will need it to sign in to your subscription.
3. Enter your administrator ID and password on the sign in page.
4. Consent to the permissions as an administrator of your Microsoft 365 developer subscription.
5. Configure your passwords for all sample users. You will need to have one shared password defined for easy administration of all your fictitious users.
6. The data will be installed. The installation should take about 5 minutes.
7. When installation is finished, you'll be notified by email, and the box on your subscription tile will be green. You can now install the Mail and Events sample data pack.

### Install the Mail & Events sample data pack

After you've installed the Users sample data pack, you can install mail and events.

1. Choose the **Mail &amp; Events** box on your subscription tile.
2. Select **Install** to begin installation.

  > [!NOTE]
  > If you just created your subscription, it must be fully provisioned before installation can begin. This can take up to a few hours. After installation starts, it can take up to 20 minutes to finish.

3. When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.

## Can I install sample data packs on my other Microsoft 365 subscriptions?

No. These sample data packs are only compatible with the Microsoft 365 developer subscription you get as part of the Microsoft 365 Developer Program.

## How can I see the sample data in my subscription?

To see the Users sample data, go to the [**Microsoft 365 Admin Center**](https://admin.microsoft.com/) on your Microsoft 365 developer subscription. Under **Users**, select **Active users**. You will see the list of 16 users. You can select a user to view the associated metadata, including photos and licenses.

![Screenshot of 16 users in the Microsoft 365 Admin Center, with metadata for a selected user](images/content-packs-07.PNG)

To see the Mail & Events sample data, in the [**Microsoft 365 Admin Center**](/microsoft-365/admin/admin-overview/about-the-admin-center), choose **Show all** and then select **Exchange**. In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.
![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)

To see the Microsoft Teams sample data, go to **Teams** in your Microsoft 365 E5 subscription. On the Teams tab, you'll see some pre-created teams with chats from sample users in the **Mark 8 Project Team**. The App Studio/Dev Portal app is pre-installed and pinned to the navigation pane.

## Related content

- [Request a Microsoft 365 developer subscription](microsoft-365-developer-program-get-started.md)
