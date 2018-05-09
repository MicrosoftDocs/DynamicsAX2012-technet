---
title: About registration groups for time and attendance
TOCTitle: About registration groups for time and attendance
ms:assetid: 49c4d7c0-727c-4abc-8f36-819f209b4fe4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa497007(v=AX.60)
ms:contentKeyID: 39519120
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- group
- approval
- calculation
- flex
- profile
---

# About registration groups for time and attendance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you set up workers as time registration workers, you can assign them to calculation groups, approval groups, profile groups, and flex groups. Only time registration workers can register absence or the time they spend on particular jobs, for example.

## Calculation groups

A calculation group typically consists of a specific team, shift, or work group. Calculation is performed to validate the registrations made by workers. The team leader or supervisor is often responsible for calculating registrations for the workers in the group. The user who calculates registrations can do the following:

  - Override the work time profile for a worker when the user performs a calculation. For more information, see [About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md).

  - View and approve switch codes.

  - Create or edit absence registrations.

  - Edit feedback on production jobs. For more information, see [About production feedback](about-production-feedback.md).

  - Create clock-out registrations if workers forgot to clock out. For more information, see [About adding clock-out registrations](about-adding-clock-out-registrations.md).

## Approval groups

To generate pay items that can be transferred to a payroll system, you must approve the registrations. Registrations can be approved only after they have been calculated, and only if no errors occurred during calculation. After you approve the registrations, you can transfer them. The registrations are allocated to specific production orders, projects, or other relevant journals.

Typically, a manager or payroll administrator from the financial department approves and transfers the daily registrations. The user who approves registrations can perform the same tasks as the user who performs calculations. Additionally, the user can do the following:

  - Override pay agreements for specific workers. For more information, see [About payroll in Time and attendance](about-payroll-in-time-and-attendance.md).

  - Add premium lines to workers’ registrations.

  - Allocate overtime costs to specific jobs.

## Profile groups

Use profile groups to connect a worker's clock-in time and the work time profile that is applied to the worker. For more information, see [About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md).

When you create workers as time registration workers, you connect them to a profile group. When the worker clocks in, the selected profile is used to calculate work hours.

For example, if workers work day, evening, and night shifts, the profile group can cover a 24-hour period. In this case, the setup is as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Clock-in time</p></th>
<th><p>Profile that is applied</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>00:00 to 03:00</p></td>
<td><p>Night</p></td>
</tr>
<tr class="even">
<td><p>03:00 to 12:00</p></td>
<td><p>Day</p></td>
</tr>
<tr class="odd">
<td><p>12:00 to 19:00</p></td>
<td><p>Evening</p></td>
</tr>
<tr class="even">
<td><p>19:00 to 00:00</p></td>
<td><p>Night</p></td>
</tr>
</tbody>
</table>


If the worker clocks in between 12:00 and 19:00, the system applies the evening profile when it calculates work hours.

## Flex groups

Workers who can work flexible hours must be assigned to a flex group that specifies how flextime registrations are handled. For more information, see [Create flex groups for time and attendance](create-flex-groups-for-time-and-attendance.md).

## See also

[About time registration workers](about-time-registration-workers.md)

[Set up calculation and approval groups for time and attendance](set-up-calculation-and-approval-groups-for-time-and-attendance.md)

[Set up profile groups for time and attendance registrations](set-up-profile-groups-for-time-and-attendance-registrations.md)

[Create flex groups for time and attendance](create-flex-groups-for-time-and-attendance.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

