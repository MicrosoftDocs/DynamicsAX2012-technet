---
title: About profiles for time and attendance registrations
TOCTitle: About profiles for time and attendance registrations
ms:assetid: b3a5efe4-d853-4caf-ab70-1a05da019d6c
ms:mtpsurl: https://technet.microsoft.com/library/Aa572016(v=AX.60)
ms:contentKeyID: 36059070
author: tonyafehr
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About profiles for time and attendance registrations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Profiles are used to define the standard working hours for workers. The profiles must cover all work hours in a week to be able to calculate the work hours and pay time for each worker.

You can set up work time profiles in the **Profiles** form. Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Profiles**.

A work time profile can cover more than 24 hours and can start on one weekday and end on another. The worker's work hours are calculated according to the profile.

## How is a profile applied to a worker?

A profile is applied to the worker when he or she clocks in. This connection is set up by applying the clock-in time to the worker's profile group.

To apply a specific work time profile to a worker on a specific day, regardless of the clock-in time, you can use the profile calendar. For more information, see [About profile calendars for time and attendance registrations](about-profile-calendars-for-time-and-attendance-registrations.md).

If a worker does not appear for work, and no profile is set up in the profile calendar, the standard work time profile selected for the worker is used. The standard profile is selected when the worker is created as a time registration worker in **Time and attendance**. See also [About time registration workers](about-time-registration-workers.md).

## Profile example

The following table shows an example of a work time profile for a worker on a specific workday.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Profile type</p></th>
<th><p>Start</p></th>
<th><p>End</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Overtime</p></td>
<td><p>00:00</p></td>
<td><p>07:00</p></td>
</tr>
<tr class="even">
<td><p>Clock-in</p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
</tr>
<tr class="odd">
<td><p>Standard time</p></td>
<td><p>07:00</p></td>
<td><p>12:00</p></td>
</tr>
<tr class="even">
<td><p>Break</p></td>
<td><p>12:00</p></td>
<td><p>12:30</p></td>
</tr>
<tr class="odd">
<td><p>Standard time</p></td>
<td><p>12:30</p></td>
<td><p>15:00</p></td>
</tr>
<tr class="even">
<td><p>Clock-out</p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
</tr>
<tr class="odd">
<td><p>Overtime</p></td>
<td><p>15:00</p></td>
<td><p>23:59</p></td>
</tr>
</tbody>
</table>


For more detailed profile examples, see [Examples: Profiles for time and attendance registrations](examples-profiles-for-time-and-attendance-registrations.md).

The norm time of this profile is 7.5 hours for the day because the break in the profile is not paid for by the legal entity.


> [!NOTE]
> <P>The profile types displayed earlier are suggestions for profile types that may be useful in your legal entity. Click <STRONG>Human resources</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Time and attendance</STRONG> &gt; <STRONG>Time profiles</STRONG> &gt; <STRONG>Profile types</STRONG>.</P>



## Tolerance

If the worker clocks in eight minutes before the scheduled start time, eight minutes of overtime are registered. To prevent this, you can set up a tolerance. Tolerances can be set up for clock-in and clock-out registrations and before or after other profile types, if it is required.

Tolerances are set up in the profile in the **Tolerance before start**, **Tolerance after start**, **Tolerance before end**, and **Tolerance after end** fields.

## Breaks

Breaks can be set up as fixed breaks in the work time profile setup, or workers can make a registration when they go on a break.

Breaks may be paid by the legal entity (**Paid break**). Otherwise the break time will be deducted from the work time.

If a break is set up in the profile, it can be canceled by using an indirect activity that cancels a break. In the **Secondary** field in the **Profile** form, you can enter a profile to use if a break is canceled. See also [About indirect activities for time and attendance](about-indirect-activities-for-time-and-attendance.md).

## Switch code

The **Secondary** field in the **Profile** form can also be used together with the **Switch code** field.

If the switch code set up in the profile is registered by the worker during the work day, the secondary profile type is applied. In some cases, the switch code requires approval during calculation of the worker’s registrations.

## Working flexible hours

If workers can use flextime and work flexible hours, you can use the profile types **Flex+** and **Flex-**.

  - **Flex+** indicates that the flex balance is increased if the worker is at work. Typically, the **Flex+** periods are put before clock-in and after clock-out.

  - **Flex-** indicates that hours are deducted from the flex balance if the worker is not at work. Typically, the **Flex-** periods are put between clock-in and clock-out times.

## Profiles without fixed clock-in or -out

If workers have no fixed clock-in or clock-out time, you can use the **Overtime / flex limit** and **Max. flex limit** fields in the profile to handle working hours and, if it is needed, also to handle the flex balance.

## 24-hour period start

Typically, on night shifts, workers clock in on one day and clock out the next day. In case the worker’s registrations are to be connected to the day of the clock-out registration, you must fill in the **New 24-hour period** and **24-hour period start** fields in the profile.

## Example

If you enter 22:00 in the **New 24-hour period** field on the profile for Monday, it indicates that the Tuesday profile is used if the worker clocks in after 22:00 on Monday.

In the profile created for Tuesday, the first type must start before 22:00. Also, the **24-hour period start** field must be set to **Previous day**. This indicates that the time for the first profile type is on Monday. The profile type **Clock in** must be set to later than 22:00 on Tuesday.

## Issues to consider before setting up work time profiles

  - **Flexible hours**
    
      - Does the legal entity employ workers who can work flexible hours?
    
      - What are the minimum and maximum values for a flex balance?

  - **Breaks**
    
      - Does the legal entity have fixed breaks?
    
      - Are these breaks paid by the legal entity?

  - **Overtime**
    
      - When does the legal entity pay for overtime?
    
      - Can overtime be handled by using switch codes?

  - **Tolerance**
    
      - Are tolerances required for clock-in and clock-out?
    
      - Are tolerances required for other profile types during a work day?

  - **Fixed profiles**
    
      - Does a worker need more than one profile?
    
      - Does the legal entity need special profiles for holidays?

  - **Shift work**
    
      - Does the legal entity use two or three shifts?
    
      - Does a shift rotation schedule have to be considered?

## See also

[Examples: Profiles for time and attendance registrations](examples-profiles-for-time-and-attendance-registrations.md)

[About registration groups for time and attendance](about-registration-groups-for-time-and-attendance.md)

[Set up profiles for time and attendance registrations](set-up-profiles-for-time-and-attendance-registrations.md)

[Set up profile groups for time and attendance registrations](set-up-profile-groups-for-time-and-attendance-registrations.md)

  


