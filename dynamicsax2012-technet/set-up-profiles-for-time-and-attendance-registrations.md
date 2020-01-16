---
title: Set up profiles for time and attendance registrations
TOCTitle: Set up profiles for time and attendance registrations
ms:assetid: 9e1874db-3676-4f0b-b679-a7395d5cad8c
ms:mtpsurl: https://technet.microsoft.com/library/Aa571725(v=AX.60)
ms:contentKeyID: 36058752
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up profiles for time and attendance registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A profile is a template for a work day that defines how a 24-hour period is divided into different types of work time. This is done by using profile types that describe how work time is calculated.

Create profiles for workers who will register time in time and attendance or manufacturing execution.

## Create a profile

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Profiles**.

2.  Click **New** to create a new line.

3.  In the **Profile** field, type a name for the profile.

4.  In the **Description** field, type a description for the profile.

5.  Click the **General** FastTab.

6.  In the **Profile** section, press CTRL+N to create a new line.

7.  In the **Profile type** field, select the **Profile type** for this profile line.

8.  Enter starting and ending work times in the **Start** and **End** fields for the selected profile type.

9.  If necessary, you can create tolerances on a profile type line. A tolerance is a period, in minutes, before or after the job has started or ended. The profile type is still valid if registrations are made within the tolerance period. Enter tolerances in minutes in the **Tolerance before start**, **Tolerance after start**, **Tolerance before end**, and **Tolerance after end** fields.

10. Use the **Switch code** field to enable workers to make a registration on an alternative profile type than the one inserted in the profile.
    
    For example, if you have included a **Flex+** profile type in your profile, you can enable workers who have flextime to be able to convert registered flextime into overtime. In that case, in the **Switch code** field, select the option for converting flex time into overtime.

11. You can enable workers to cancel breaks in their profile. This might be useful in a situation where a supervisor asks workers to cancel all breaks for the workday so that rush orders can be completed. In that case, you must select an alternative profile type to the **Break** profile type. The alternative profile is as a basis for calculating time registrations if the worker cancels the break.

12. In the **Secondary** field, on the **Break** profile type line, select the profile type that should replace a **Break** profile type, for example, **Overtime**.

13. In the **Start day** and **End day** fields, select the appropriate workday, according to the selections you made in the **Start** and **End** fields in step 8.
    

    > [!NOTE]
    > <P>Typically, you select the same weekday as the day that you are creating the profile for. However, if you are creating a profile for a night shift, a profile type may start late in the evening on one weekday and end after midnight on the following week day. In that case, you must select one weekday in the <STRONG>Start day</STRONG> field, and the following weekday in the <STRONG>End day</STRONG> field.</P>



## Copy one weekday to other weekdays

When you have created one weekday in a profile, the easiest way to set up the other weekdays is to copy that first weekday, and then adjust the other days, as needed.

1.  In the **Profile** form, on the **General** tab, select the weekday to copy in the **Weekday** section.

2.  Click **Copy**, and select **Copy day**.

3.  Select the weekdays to copy the profile to, and select the **Overwrite** check box.

4.  If necessary, adjust the other weekdays if they have different profiles from the weekday that you copied.

## Copy an entire profile for a week

If you have already created a work time profile covering a whole week, you can copy the entire profile and then make adjustments to the new profile, as needed.

1.  In the **Profile** form, select the profile to copy.

2.  Click **Copy**, and select **Copy profile**.

3.  Enter the name of the new profile in the **Copy to** field.
    

    > [!NOTE]
    > <P>To overwrite an existing profile, select that profile in the <STRONG>Copy to</STRONG> field, and then select the <STRONG>Overwrite</STRONG> check box.</P>



## Other considerations

Profiles can be set up for various types of work situations. The following information describes additional considerations if you are creating special work time profiles.

## Profile days that traverse midnight

If your company works night shifts, the profile day might start before midnight. If so, you can make the following adjustments for the night shift profile on the **General** tab, in the **Profile staggering** section:

  - In the **New 24-hour period** field, enter a starting time for the next profile day.

  - In the **24-hour period start** field, select **Previous day**.


> [!TIP]
> <P>If you want registrations made in the current day to apply to the next 24-hour period, select the <STRONG>Push</STRONG> check box.</P>



## Workers without a fixed clock-in or clock-out time

Some workers may not have fixed work hours. Consequently, the **Overtime / flex limit** and **Max. flex limit** fields on the **General** tab can be used to determine **Standard time** in hours, and the maximum number of flexible hours allowed before converting registered time into overtime.

For example, if you insert the number 40 in the **Overtime / flex limit** field, and the number 10 in the **Max. flex limit** field, it means that the worker has a 40-hour work week. If the worker works more than 50 hours during a week, 40 hours are considered standard work time, 10 hours are added to the flex balance, and the number of hours exceeding 50 hours is considered to be overtime.

## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About profile types for time and attendance registrations](about-profile-types-for-time-and-attendance-registrations.md)

[Examples: Profiles for time and attendance registrations](examples-profiles-for-time-and-attendance-registrations.md)

  


