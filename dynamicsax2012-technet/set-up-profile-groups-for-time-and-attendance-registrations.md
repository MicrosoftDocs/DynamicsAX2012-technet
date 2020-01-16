---
title: Set up profile groups for time and attendance registrations
TOCTitle: Set up profile groups for time and attendance registrations
ms:assetid: d6f43b54-f02d-47d1-a646-d935518af5a3
ms:mtpsurl: https://technet.microsoft.com/library/Aa499485(v=AX.60)
ms:contentKeyID: 39519333
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up profile groups for time and attendance registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use profile groups to set up one or more work time profiles in the same group. The profiles are used to calculate, for example, work time and overtime for a worker based on the worker’s clock-in time.

## Create a profile group

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Profile groups**.

2.  Press CTRL+N to create a new line.

3.  In the **Profile group** field, type a name.

4.  In the **Description** field, type a description of the profile group.

5.  Click **Profile relation** or **Profile calendar** to create profile relations or profile calendars.

## Create a profile relation for a profile group

After you have created a profile group, you need to add the work time profiles that should be available in the group.

1.  In the **Profile groups** form, select a profile group in the list.

2.  Click **Profile relation**.

3.  In the **Profile relation** form, click **New** on the toolbar.

4.  In the **Profile** field, select a profile.

5.  In the **From time** field, type the start time for applying this profile to a worker.

6.  In the **To time** field, type the end time for applying this profile to a worker.

7.  Complete the remaining fields.
    

    > [!NOTE]
    > <P>Only use these fields when profile selections vary during the calendar year. For example, if a company uses three shifts in the winter and two shifts in the summer, you can apply this changing shift work to the profile group by filling out the <STRONG>From day</STRONG>, <STRONG>From month</STRONG>, <STRONG>To day</STRONG>, and <STRONG>To month</STRONG> fields.</P>



8.  Continue to create profile relations for all the profiles to be used in the profile group.

## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About registration groups for time and attendance](about-registration-groups-for-time-and-attendance.md)

[About profile calendars for time and attendance registrations](about-profile-calendars-for-time-and-attendance-registrations.md)

  


