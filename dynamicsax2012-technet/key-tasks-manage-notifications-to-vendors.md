---
title: 'Key tasks: Manage notifications to vendors'
TOCTitle: 'Key tasks: Manage notifications to vendors'
ms:assetid: aa34282a-d7b7-4067-a795-c13c4aacda77
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242691(v=AX.60)
ms:contentKeyID: 36058901
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Manage notifications to vendors 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create notifications to send electronically to one or more vendors. Vendors with access to the vendor self-service portal can view notifications in the vendor self-service portal, and vendor contacts can receive notifications in their e-mail. For example, use notifications to inform your vendors about new procedures when they use the vendor self-service portal, or to notify only the vendors associated with a specific procurement category to respond to a new questionnaire for the category.

Before you can send notifications via e-mail message to vendors, your system administrator must set up e-mail parameters in Microsoft Dynamics AX. For more information about e-mail parameters, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

## What do you want to do?

Create a vendor notification

Copy a vendor notification

Translate a notification to another language

Delete a vendor notification

Find form help

Find related tasks

## Create a vendor notification

Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **Vendor notifications**.

1.  Click **New**.

2.  In the **Topic** field of the **Details** FastTab, enter a description of the notification. The topic is the internal description of the notification.

3.  Enter the due date for the notification. This is the date on which the notification is no longer valid.

4.  Select the **Send e-mail message** check box to send a notification to the e-mail address of the selected vendor’s primary contact. You can only send notifications to vendor contacts who have indicated in their profile that they want to receive notifications electronically.

5.  Select recipients on the **Selection** FastTab. You can select recipients by filtering on vendor profile data, such as a location, or by filtering on procurement categories.
    
      - To filter for a specific vendor, vendor contact, a group of vendors, or a group of vendor contacts, click **Select**. On the **VendNotificationTemplate** form, select a **Field** and the related **Criteria**. All vendors and contacts that meet your selection criteria will be sent the notification.
    
      - You can select vendors associated with specific procurement categories. By default, all categories are selected. The selections that you make in the **Category filter** section replace any selections you made in the **Recipient filter** section.

6.  Enter a subject for the notification. This is the subject that vendors will see in the list of notifications on the vendor self-service portal and in the subject field of the e-mail message.

7.  Create the text of the message.

8.  Save the message. You must save a message before you can send it, copy it, or attach a file to it. The notification has a status of **Not sent**.

9.  Click **Attachments** to add a file as an attachment to the notification.

10. Click **Send** to send the notification to the selected vendors. Vendors with access to the vendor self-service portal can view the message and any attachments. For more information about the vendor self-service portal, see [Key tasks: Manually set up user access to the Vendor portal](key-tasks-manually-set-up-user-access-to-the-vendor-portal.md).

Back to top

## Copy a vendor notification

Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **Vendor notifications**.

1.  In the left pane, select the notification that you want to copy.

2.  Click **Copy**.

3.  The **Topic**, recipients, **Subject**, and **Message** are copied to a new notification.

4.  You can modify the copied notification, such as adding or removing recipients.

5.  Save the message. You must save a message before you can send it, copy it, or attach a file to it. The notification has a status of **Not sent**.

6.  Click **Send**. The notification has a status of **Sent**.

Back to top

## Translate a notification to another language

Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **Vendor notifications**.

1.  In the left pane, select the notification that you want to translate.

2.  On the **Message** FastTab, click **Create message** to enter the message in another language.

3.  In the left pane of the **Translation text: Vendor notification message** form, select a language.

4.  Enter the subject in the selected language.

5.  Enter the message in the selected language.

6.  Save the message. You must save a message before you can send it, copy it, or attach a file to it. The notification has a status of **Not sent**.

7.  On the **Selection** FastTab, select the recipients of the notification.

8.  Click **Send**.

Back to top

## Delete a vendor notification

Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **Vendor notifications**.

1.  In the left pane, select the notification that you want to delete.

2.  Click **Delete**, and then confirm the deletion.

Back to top

## Find form help

[Vendor notifications (form)](https://technet.microsoft.com/en-us/library/hh242813\(v=ax.60\))

[Translation text: Vendor notification message (form)](https://technet.microsoft.com/en-us/library/hh227658\(v=ax.60\))

## Find related tasks

[Communicate with your vendors overview](communicate-with-your-vendors-overview.md)

  


