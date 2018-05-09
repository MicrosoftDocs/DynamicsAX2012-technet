---
title: Time zones and activities
TOCTitle: Time zones and activities
ms:assetid: 6afb2837-cdc4-4521-90dd-229a0a5c1bf8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231782(v=AX.60)
ms:contentKeyID: 36057985
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Time zones and activities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Many companies have customers who are located in other time zones, and some companies themselves have different locations across the world. Multiple time zones can make scheduling activities difficult, because you must calculate the time difference between participants. By using the time zone functionality in Microsoft Dynamics AX, you can create and synchronize activities in relation to the time zones that are set up in Microsoft Outlook. Time values are stored in Microsoft Dynamics AX as Coordinated Universal Time (UTC). However, when you view the times for activities, the times are displayed in the time zone in which you are located.

Activities in Microsoft Dynamics AX are divided into the following four categories:

  - Appointment

  - Task

  - Event

  - Action

When you create an activity, you can set a start date and time, and an end date and time. Tasks and events are the exception, because these types of activity do not have a field for the end date and time. For both the start and end of an activity, the date and time information is located in the same field.

After you create the activity and determine the date and time, you can synchronize the activity to your calendar in Microsoft Outlook.

**Example**

You are located in Copenhagen, Denmark. You want to schedule an activity that involves attendees who are located in two other cities, each of which is in a different time zone: New Delhi, India, and Buffalo, New York. When you create the activity, the date and time that you set reflect your time zone. You create the activity in your calendar for August 15 at 16:00.

When you assign the activity to the attendee in Buffalo, New York, the date and time of the activity appear to the attendee as August 15 at 10:00. When you assign the activity to the attendee in New Delhi, India, the date and time appear to the attendee as August 16 at 20:00.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

