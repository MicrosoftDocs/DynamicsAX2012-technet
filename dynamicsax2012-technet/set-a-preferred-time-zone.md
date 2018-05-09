---
title: Set a preferred time zone
TOCTitle: Set a preferred time zone
ms:assetid: f12c3cd8-192f-40a6-9177-bd7774c8beec
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243274(v=AX.60)
ms:contentKeyID: 36059928
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- select a time zone
- Timezone
- Time Zone
---

# Set a preferred time zone 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set a time zone for times and dates. Your preferred time zone is first set according to your Windows locale, although it may have been changed by an administrator.


> [!NOTE]
> <P>If your preferred time zone does not match that of your Windows locale, every time that you start a Microsoft Dynamics AX client, you will be notified that they do not match.</P>



Your preferred time zone is used only when displaying dates and times. Date and time values are stored in Coordinated Universal Time (UTC). UTC is the standard time that is common to every location in the world, coordinated by the International Bureau of Weights and Measures. Storing dates and times in UTC enables Microsoft Dynamics AX to support multiple time zones.

## Set your preferred time zone

1.  From a Microsoft Dynamics AX client, click **File** \> **Tools** \> **Options...**.

2.  Click **General**. In the **Preferred time zone** field, select a time zone.

3.  Close the form to save your changes.

## See also

[About date/time data and time zones](about-date-time-data-and-time-zones.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

