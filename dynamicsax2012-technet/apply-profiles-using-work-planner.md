---
title: Apply profiles using work planner
TOCTitle: Apply profiles using work planner
ms:assetid: db3da17d-6971-42d8-b433-ebe4d3e5dcfd
ms:mtpsurl: https://technet.microsoft.com/library/Aa551234(v=AX.60)
ms:contentKeyID: 36059666
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Apply profiles using work planner 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Work planner** to apply work time profiles to workers or a group of workers. This is useful when you want to change a worker’s work plan because it differs from the standard profile. When you save a work plan, the records are transferred to the **Profile calendar**.

## Apply profiles using work planner

1.  Click **Human resources** \> **Periodic** \> **Time and attendance** \> **Work planner**.

2.  In the **Date interval** section, select the appropriate dates. The standard period displayed is this month.

3.  To highlight Saturdays and Sundays, select the **Show weekend** check box.

4.  In the **Profiles** section, click a profile color to select the profile.
    

    > [!NOTE]
    > <P>Click <STRONG>Human resources</STRONG> &gt; <STRONG>Reports</STRONG> &gt; <STRONG>Time and attendance</STRONG> &gt; <STRONG>Work planner</STRONG> &gt; <STRONG>Profile</STRONG>.</P>



5.  To apply the selected profile, click in the date fields for the relevant worker in the **Workers** section.
    

    > [!NOTE]
    > <P>You can also apply profiles to profile groups or all workers on the <STRONG>Profile group</STRONG> tab.</P>



6.  Repeat the steps earlier in this section until you have created all the necessary profile records.

7.  When your plan is finished, click **Save** to transfer the entries to the **Profile calendar**.

## Copy a profile interval

Workers might have a work plan, or work cycle, that includes more than one work time profile during a work week. For example, this could be day shifts Monday through Wednesday, and evening shifts Thursday through Friday. In this case, first create one work week, and then copy the interval to other work weeks.

1.  Follow the previous procedure to create a work week, or work cycle, for a worker or a profile group.

2.  Click the **Copy interval** button.

3.  In the **Profile calendar code** field, select whether the interval should be copied to all workers, a specific worker, or a group of workers.

4.  In the **Profile calendar relation** field, enter worker ID or profile group ID, depending on the selection in the **Relation type** field.

5.  In the **From date** and **To date** fields, define the period to which you want to copy the work week or work cycle.

6.  In the **Number of repeats** field, insert the number of times the copy should occur.

7.  Select the **Overwrite** check box to delete existing profile entries for the selected worker or profile group and replace them with the entries you create.

8.  Click **OK**.

## Delete selections in the work planner

There are two ways to delete your selections in the work planner:

  - Click the **Clear changes** button to delete all selections that you have not saved yet.

  - Select the **Clear profile** check box, and then clear the fields in the **Workers** section where the wrong selections were made by clicking them.

## Apply a profile for a longer period of time

You can also use the **Compose profile calendar** functionality to apply a profile to workers or profile groups for a longer period of time.

1.  In the **Work planner** form, click the **Compose** button.

2.  In the **Profile calendar code** field, select whether you want to apply another work time profile to all workers, a specific worker, or group of workers.

3.  In the **Profile calendar relation** field, enter worker ID, or profile ID of the profile group.

4.  Define the date interval in the **From date** and **To date** fields.

5.  In the **Profile** field, select the profile to be applied.

6.  Select the **Overwrite** check box to delete existing profile entries for the selected worker or profile group, and replace them with the entries you create.

7.  Click OK.

## See also

[About work planner](about-work-planner.md)

[About profile calendars for time and attendance registrations](about-profile-calendars-for-time-and-attendance-registrations.md)

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

  


