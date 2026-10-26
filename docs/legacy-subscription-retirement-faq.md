---
title: Retirement of legacy Microsoft 365 developer subscriptions
description: Learn what's changing for legacy Microsoft 365 developer subscriptions, when it happens, and how to set up a new subscription and move your work.
ms.date: 10/26/2026
ms.localizationpriority: high
---

# Retirement of legacy Microsoft 365 developer subscriptions

The Microsoft 365 Developer Program is retiring legacy developer subscriptions. If your subscription is labeled **Legacy sandbox** on your [Developer Program dashboard](https://developer.microsoft.com/microsoft-365/profile), this article explains what's changing, when it happens, and what you can do. Your developer subscription is also referred to as your sandbox.

## About this change

### Which subscriptions are affected?

Your subscription is affected if it's labeled **Legacy sandbox** on your Developer Program dashboard. Instant sandboxes with add-on purchases enabled aren't affected. This change retires the legacy subscription only. It doesn't affect your Developer Program membership.

### I don't see a Legacy sandbox label. Am I affected?

No. If your subscription isn't labeled **Legacy sandbox**, this change doesn't affect it.

### I have a Visual Studio subscription. Why is my subscription being retired?

Legacy subscriptions are being retired for all members, including Visual Studio Professional and Enterprise subscribers. Your Visual Studio subscription doesn't extend a legacy subscription beyond its final renewal. If you're still eligible, you can set up a new subscription, which supports add-on purchases.

### When will this happen to my subscription?

Your legacy subscription gets one final 60-day renewal, starting on the day you're notified. It then expires on the date shown on your Developer Program dashboard, and it's permanently deleted 120 days after you're notified. Your notification email also includes the exact dates for your subscription.

| When | What happens | What you should do |
|---|---|---|
| Day 0 (you're notified) | Your subscription gets its final 60-day renewal. | Check your eligibility and set up a new subscription. |
| Days 0–60 | Your legacy subscription stays active. | Move your work to your new subscription. |
| Day 60 | Your legacy subscription expires. | Finish copying out anything you want to keep. |
| Days 60–120 | Your legacy subscription is inactive. Only the admin can sign in for data recovery. [Confirm access during this window.] | Back up anything you still need. |
| Day 120 | Your legacy subscription and all its data are permanently deleted. | Nothing can be recovered after this date. |

### How will I be notified?

We email the address on your Developer Program account at two points: when your subscription gets its final renewal and when it's deleted.

### Can I extend, convert, or transfer my legacy subscription?

No. After its final renewal, a legacy subscription isn't renewed again, regardless of development activity or Visual Studio subscription status. It can't be converted to a subscription with add-on purchases enabled, and its benefits can't be transferred to another subscription. To keep developing, you can set up a new subscription if you're eligible. For eligibility details, see [Microsoft 365 Developer Program FAQ](microsoft-365-developer-program-faq.yml).

### Can I get more time or an exception?

No. The dates for your subscription are final, and we can't extend them or make exceptions. Start moving your work early so you have time to finish before your subscription expires.

## Set up a new subscription

### Am I eligible for a new subscription?

For the full eligibility details, see [Microsoft 365 Developer Program FAQ](microsoft-365-developer-program-faq.yml).

### How do I set up a new subscription?

If you're eligible, you can set up a free Microsoft 365 E5 developer subscription with 25 user licenses, including the admin. It's provisioned as an instant sandbox with sample data, and it supports add-on purchases such as Microsoft 365 Copilot licenses.

For detailed steps, see [Set up a Microsoft 365 developer sandbox subscription](microsoft-365-developer-program-get-started.md).

### Why do I need a billing account to set up the new subscription?

A billing account is required to set up a new sandbox. It's used to verify your identity and to enable optional purchases. You won't be charged for the sandbox itself. For requirements, see [Configure billing details](microsoft-365-developer-program-get-started.md#step-2-configure-billing-details).

### Can I set up the new subscription before my legacy one expires?

Yes. If you're eligible, you can set up your new subscription as soon as you're notified. [Confirm the setup option is available from Day 0.] Setting up early gives you the most time to move your work.

### Can I keep using my legacy subscription while I set up the new one?

Yes. Your legacy subscription remains active until its expiry date, which is shown on your Developer Program dashboard. You can set up the new subscription and move your work across before then. Nothing transfers automatically: your new subscription has a new domain name and doesn't include any data or settings from your legacy subscription.

## Move your work

### What should I move before my subscription is deleted?

Anything that exists only in your legacy subscription is deleted with it, and you're responsible for copying out anything you want to keep. Your new subscription is a separate tenant with a new domain name and tenant ID, so plan to re-create or redeploy your work rather than copy it across directly. Check these items:

- **Apps and registrations:** Microsoft Entra app registrations (client IDs, secrets, certificates, redirect URIs, and API permissions), Teams app packages, SharePoint Framework (SPFx) solutions, Office add-ins, Copilot agents, and bot registrations. Register and deploy them again in your new subscription, then grant admin consent.
- **Code and configuration:** source code, scripts, environment settings, and CI/CD pipelines that reference your old tenant ID, domain name, app IDs, or user accounts.
- **Power Platform solutions:** [export your Power Apps, Power Automate flows, and Dataverse customizations as solutions](/power-apps/maker/data-platform/export-solutions), then import them and re-create connections in your new subscription.
- **Content:** files, SharePoint sites and lists, OneDrive content, and Teams channels and files that you need for testing.
- **Mail and calendars:** any test mailboxes or calendar data you rely on.
- **Users, groups, and settings:** test users, groups, licenses, and admin or security settings that your solutions depend on. Your new subscription includes its own sample users and data.

For guidance, see how to [migrate mailboxes across tenants](/microsoft-365/migration/cross-tenant-mailbox-migration) and how to [migrate content to Microsoft 365](/sharepointmigration/migrate-to-sharepoint-online). Most developers find it simpler to export what they need and redeploy it, because cross-tenant migration tools can require additional licenses.

### What if I'm not eligible for a new subscription?

Your legacy subscription is retired on the same schedule, and there's no replacement subscription. Copy out anything you want to keep before your deletion date. To keep developing, you can get a sandbox through a Visual Studio Professional or Enterprise subscription or an eligible partner program, or use a Microsoft 365 trial or paid plan.

## After deletion

### Can a deleted subscription be restored?

No. Deletion is permanent and can't be reversed by you or by Microsoft. [Legal to confirm this wording.] If you're eligible, you can set up a new subscription, but it won't include any of your previous data.

## Help and terms

### Where can I get help?

If you have trouble setting up a new subscription, see the troubleshooting section of [Set up a Microsoft 365 developer sandbox subscription](microsoft-365-developer-program-get-started.md#troubleshooting), which also explains how to contact Developer Program support.

### Which terms apply?

Your use of the program, including your developer subscription, is governed by the [Microsoft 365 Developer Program terms and conditions](terms-and-conditions.md).

## Related content

- [Microsoft 365 Developer Program FAQ](microsoft-365-developer-program-faq.yml)
- [Set up a Microsoft 365 developer sandbox subscription](microsoft-365-developer-program-get-started.md)
- [Microsoft 365 Developer Program terms and conditions](terms-and-conditions.md)
