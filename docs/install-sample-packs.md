---
title: Use sample data packs with your Microsoft 365 Developer Program subscription
description: Learn how to install sample data packs on your developer subscription to help get your sandbox environment up and running quickly. 
ms.localizationpriority: high
---

# Use sample data packs with your Microsoft 365 Developer Program subscription

Your Microsoft 365 Developer Program sandbox subscription comes with sample data to save you time by providing data and content you need to build and test your solutions.

![Screenshot of the sample data pack buttons](images/sample-data-packs.PNG)

## Sample data installed on the instant sandbox

If you have an instant sandbox, the sample data packs are already pre-installed. Your instant sandbox includes the following sample data:

- **Microsoft Graph user, mail, and calendar data** - 16 sample users with user data and content to help you model your solutions. This includes user mailboxes, calendar events, and integration into a Teams developer environment with simulated chats and team memberships.
- **Teams sample data** pack with the following customized developer environment:
  - **App sideloading** pre-configured
  - **Five sample teams, channels, tabs, and chat sessions** built around the 16 sample users.
  - **App Studio / Teams Developer Portal pre-installed and pinned** to help you streamline the creation of your Teams app manifest and app package, plus the card editor and a React control library.
    
    ![Screenshot of the Teams Developer Portal](images/teams-developer-portal.PNG)
- **SharePoint Framework sample data** – Choose from six site templates that you can install and evaluate as custom solutions for your organization (with one pre-installed).

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
    
- SharePoint Framework sample data – Choose from six site templates that you can install and evaluate as custom solutions for your organization (with one pre-installed).


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

### Install the SharePoint sample data pack

The SharePoint sample data pack includes six different SharePoint site templates to choose from to experience and model SharePoint solutions for collaboration, communication, engagement, and knowledge management.

These are some of the most popular templates from the [SharePoint PnP look book](https://lookbook.microsoft.com). Today, it's simple to create sample solutions of beautiful, fast sites and pages that look great on any device or screen. Get inspired with these designs or add them to your sandbox tenant to start building your next site.

The templates can be installed on your subscription. After you install one template, you have the option to install the others. The installation process includes the following steps:

1. Select the Template you want from the drop down menu.

  ![Screenshot of the SharePoint template selection screen](images/sharepoint-sample-data.png)

2. Configure custom options for your sites, or accept the default values.
3. Use the administrator ID of your sandbox tenant and password to authenticate and give permissions to install. 

Installation will proceed automatically.

>**Note:** The provisioning of these site templates only works with English Office 365 E3 or Microsoft 365 E5 developer subscriptions, and all content included is English only.

#### What SharePoint templates are available?

The SharePoint sample pack includes seven different templates.

#### Team site with data

The Team site with data template includes multiple lists and document libraries that are automatically associated with a SharePoint team site to help you develop solutions using SharePoint Framework, Power Apps, and Microsoft Graph.

This template includes the following data:

- A contact list with pre-populated contacts
- A list populated with over 6,000 items
- Document libraries with sample PowerPoint, Excel, Word, and OneNote documents
- An events list with announcement items

This template integrates with the Users sample data.

#### Work @ Contoso
The Work @ Contoso template consists of multiple site collections that are all automatically associated with the hub site to show how all default aggregation capabilities work.

This template contains following structures and assets:

- Main site collection set as a hub site
- Two communication sites associated with the hub site - Benefits and charity sites
- One group team site associated with the hub site - Team site
- Sample news articles in the subsite collections
- Sample Word, Excel, and PowerPoint files
- Sample image content used in the site collections

Subsite collections use the same templates, which you can also provision separately from this service.

>**Note:** If this template is applied on top of an existing communication site, the welcome page content of the site will be overwritten.

#### Leadership Connection: Leadership news, events, engagement

This leadership site provides insight into the goals and priorities of the leadership team, and inspires engagement with events and conversations.

Adding this design to your tenant will create the following content:

- Example welcome page with demonstration of web parts
- Example news articles demonstrating different modern page designs

This template integrates with the Users sample data.

#### The Landing: News, resources, personalized content

This communication site is designed to be the place where your employees can find the news and resources they need, plus personalized content tailored just for them.

Adding this design to your tenant will create the following content:

- Demo structure for home site of the portal
- Custom welcome page structure
- Six additional sample modern pages and news articles
- Sample images and Office documents

#### The Perspective: News, video, personalized content

Designed to offer news and personalized content, this site also includes videos to inspire even more engagement.
Adding this design to your tenant will create the following content:

- Custom welcome page designs
- Sample page template for news articles
- 12 sample news articles

#### Crisis Communications: Announcements, news, resources, communities and calls-to-action

Keep people informed, engaged, and moving forward during crises, from extreme weather events to health and safety emergencies. This template creates a central resource for leaders and communicators to share important news and announcements, a single source of truth where people can stay up-to-date, and a place to connect people across the organization.

Adding this design to your tenant will create the following content:

- Custom welcome page built using a web part
- Four news articles with example content

This template integrates with the Users sample data.

## Can I install sample data packs on my other Microsoft 365 subscriptions?

No. These sample data packs are only compatible with the Microsoft 365 developer subscription you get as part of the Microsoft 365 Developer Program.

## How can I see the sample data in my subscription?

To see the Users sample data, go to the [**Microsoft 365 Admin Center**](https://admin.microsoft.com/) on your Microsoft 365 developer subscription. Under **Users**, select **Active users**. You will see the list of 16 users. You can select a user to view the associated metadata, including photos and licenses.

![Screenshot of 16 users in the Microsoft 365 Admin Center, with metadata for a selected user](images/content-packs-07.PNG)

To see the Mail & Events sample data, in the [**Microsoft 365 Admin Center**](/microsoft-365/admin/admin-overview/about-the-admin-center), choose **Show all** and then select **Exchange**. In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.
![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)

To see the Microsoft Teams sample data, go to **Teams** in your Microsoft 365 E5 subscription. On the Teams tab, you'll see some pre-created teams with chats from sample users in the **Mark 8 Project Team**. The App Studio/Dev Portal app is pre-installed and pinned to the navigation pane.

To see the SharePoint sample data, go to the SharePoint admin center, and choose **Active sites** in the left navigation. You can see the sample sites that are pre-installed and any additional site templates that you install in your sandbox.

## See also

- [Set up a Microsoft 365 developer subscription](microsoft-365-developer-program-get-started.md)
