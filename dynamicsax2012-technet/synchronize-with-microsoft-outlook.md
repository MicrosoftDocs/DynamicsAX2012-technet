---
title: Synchronize with Microsoft Outlook
TOCTitle: Synchronize with Microsoft Outlook
ms:assetid: 0ac7de3b-0de4-4542-9023-fd7035a0e76c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569740(v=AX.60)
ms:contentKeyID: 37822137
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- microsoft outlook
---

# Synchronize with Microsoft Outlook 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can synchronize your contacts, activities, and private and public tasks and appointments between Microsoft Dynamics AX and Microsoft Outlook.

1.  Click **File** \> **Tools** \> **Options**. In the **Options** form, click the **Microsoft Outlook** link.

2.  Click the icon next to the **Microsoft Office Outlook user identification** field to select your Outlook identifier.

3.  Select the folders in Outlook that you want to use to synchronize your contacts, tasks, and appointments from Microsoft Dynamics AX to Outlook.

4.  If you are synchronizing your appointments or tasks, enter the number of days before and after the current date to synchronize.

5.  If you want to set an activity reminder, enter the number of minutes before the start of an activity that the reminder occurs.

6.  If you want to use a default start time and end time for all activities that you create, enter the times.

7.  Select the **Save copy of sent e-mails** check box to save a copy of all email messages that you send from Microsoft Dynamics AX.


> [!IMPORTANT]
> <P>Note the following considerations about synchronization:</P>
> <UL>
> <LI>
> <P>Group activities are synchronized for Outlook appointments, but tasks are not synchronized.</P>
> <LI>
> <P>Group activities are synchronized between Microsoft Dynamics AX and Outlook only if the organizer of the activity has synchronized the activity. For group activities, the organizer must first synchronize the activity. Then either Microsoft Dynamics AX or Outlook creates or updates the activities for the attendees. If the organizer does not first synchronize the activity, the attendee activities are not synchronized.</P>
> <LI>
> <P>Recurring activities are synchronized.</P>
> <LI>
> <P>The Outlook synchronization features in the <STRONG>Sales and marketing</STRONG> module are not supported when the Microsoft Dynamics AX client is deployed by using Remote Desktop Services.</P></LI></UL>



## See also

[Add and delete contacts for synchronization in Microsoft Dynamics AX and Microsoft Outlook](add-and-delete-contacts-for-synchronization-in-microsoft-dynamics-ax-and-microsoft-outlook.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

