---
title: About profile types for time and attendance registrations
TOCTitle: About profile types for time and attendance registrations
ms:assetid: 2c71eb0f-90ca-4ae3-bd48-c4947e7dc752
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496869(v=AX.60)
ms:contentKeyID: 39519081
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About profile types for time and attendance registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Profile types provide the basis for creating work time profiles. Profiles cover a whole day, and the profile types define how a 24-hour period is divided into different types of work time. You create profile types for work time profiles in the **Profile types** form.

## Profile types

Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Profile types**.

The following table contains examples of profile types.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Profile type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Clock in</strong></p></td>
<td><p>The time when the worker is supposed to clock in for work.</p>
<p>Enter the start time for this profile type. The end time is automatically set to the same time in the <strong>Profile</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Clock out</strong></p></td>
<td><p>The time when the worker is supposed to leave work.</p>
<p>Enter the start time for this profile type. The end time is automatically set to the same time in the <strong>Profile</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>The time to be considered work hours during the calculation of registrations.</p></td>
</tr>
<tr class="even">
<td><p><strong>Overtime</strong></p></td>
<td><p>The time to be considered overtime during the calculation of registrations.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Break</strong></p></td>
<td><p>A break for which the worker does not receive pay.</p></td>
</tr>
<tr class="even">
<td><p><strong>Paid break</strong></p></td>
<td><p>A break for which the worker receives pay from the company.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Flex+</strong></p></td>
<td><p>If the worker is at work, the time is added to his or her flex balance.</p></td>
</tr>
<tr class="even">
<td><p><strong>Flex-</strong></p></td>
<td><p>If the worker is at work, the time is considered standard time. If the worker is absent, the time is deducted from his or her flex balance.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Supplement pay or bonus</strong></p></td>
<td><p>If some workers are qualified to receive supplemental pay or bonuses, specific profile types can be created for those purposes.</p>
<div class="alert"> 

> [!TIP]
> <P>You can create any number of profile types. To create a profile type that is not associated with a standard profile specification type, you can leave the <STRONG>Profile specification type</STRONG> field in the <STRONG>Profile types</STRONG> form blank.</P>


</div></td>
</tr>
</tbody>
</table>



> [!IMPORTANT]
> <P>The calculation of time registrations and pay time, based on profile types, can be managed in the <STRONG>Calculation parameters</STRONG> form. For more information, see <A href="about-parameters-for-calculations.md">About parameters for calculations</A>.</P>




> [!NOTE]
> <P>Flextime can only be calculated for a worker if it has been set up in the <STRONG>Time registration workers</STRONG> form. Click <STRONG>Human resources</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Workers</STRONG> &gt; <STRONG>Time registration workers</STRONG>. Click <STRONG>Set up time registration worker</STRONG> on the <STRONG>Time registration</STRONG> tab on the <STRONG>Action Pane</STRONG>.</P>




> [!NOTE]
> <P>Profile types can also be used in pay agreements, for example, to trigger a special kind of pay or bonus that is only generated for the workers who are connected to that particular profile type and pay agreement.</P>



## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[Examples: Profiles for time and attendance registrations](examples-profiles-for-time-and-attendance-registrations.md)

[Set up profiles for time and attendance registrations](set-up-profiles-for-time-and-attendance-registrations.md)

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[About time registration workers](about-time-registration-workers.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

