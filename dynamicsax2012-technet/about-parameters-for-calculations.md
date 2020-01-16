---
title: About parameters for calculations
TOCTitle: About parameters for calculations
ms:assetid: 1ff25cb2-5864-42af-a2c9-d7061228bba3
ms:mtpsurl: https://technet.microsoft.com/library/Aa496784(v=AX.60)
ms:contentKeyID: 36056156
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About parameters for calculations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Calculation parameters calculate work time and pay for workers. Click **Human resources** \> **Setup** \> **Time and attendance** \> **Calculation parameters**.

## Calculation parameter settings

Based on the combination of different registration specification types (**Reg. specification** section in the **Calculation parameters** form) and profile specification types (**Profile specification type** section in the **Calculation parameters** form), you can specify how time is calculated with regard to work hours and paid time.

Registration specification types relate to the various types of registrations that a worker makes. The worker’s registrations are calculated against the work time profile that is selected for the worker. The profile that the worker uses may depend on the time of day for the clock-in registration; for example, if a production department works two or three shifts during a 24-hour period.


> [!NOTE]
> <P>If the worker is not at work, and therefore, has made no registrations for one or more days, the worker’s time is calculated against the standard work time profile that has been selected for the worker, or against the work time profile that may have been selected for the worker in the <STRONG>Profile calendar</STRONG> or <STRONG>Work planner</STRONG> for the specific period.</P>



The following registration specification types can be found in the **Calculation parameters** form.

## Registration specification types

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Registration type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Working time</strong></p></td>
<td><p>The worker is at work.</p></td>
</tr>
<tr class="even">
<td><p><strong>Legal absence</strong></p></td>
<td><p>The worker is not at work, but the selected absence group does not deduct hours from the worker’s overtime or flex balances.</p>
<p>For example, this kind of absence could be the worker’s illness, or that the worker is attending an external training course.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Illegal absence</strong></p></td>
<td><p>The worker is not at work, but the selected absence group deducts hours from the worker’s overtime balance. However, the flexible hours balance is not reduced.</p>
<p>For example, this registration type can be used if the worker is late for work but plans to work additional hours the same day or another day in the week, if that is permitted.</p></td>
</tr>
<tr class="even">
<td><p><strong>Flex-reducing absence</strong></p></td>
<td><p>The worker is not at work. The selected absence group does not deduct from the worker’s overtime, but reduces the flex balance.</p>
<p>For example, this can be used if a worker takes a whole day off to reduce the flexible hours balance.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Flex-reducing illegal absence</strong></p></td>
<td><p>The worker is not at work. The absence group deducts from the worker's overtime and reduces the flex balance.</p>
<p>For example, this can be used if a worker is permitted to work flexible hours, but clocks in after the end of the flex-period tolerance without having a valid excuse for the absence.</p></td>
</tr>
<tr class="even">
<td><p><strong>Work-free flex zone</strong></p></td>
<td><p>The worker is not at work in a flexible hours-reducing time zone. The worker receives pay for the time, and the flex balance is reduced.</p></td>
</tr>
</tbody>
</table>


## Absence groups

Absence groups are used to handle various types of absence registrations for a worker. Click **Human resources** \> **Setup** \> **Absence** \> **Absence groups**. If the check boxes are selected for a particular absence group, it means that one of the following conditions is true:

  - The flex balance is reduced.

  - Time is deducted from the overtime balance, if absence codes in that absence group are registered by workers.

  - Both of the previous conditions are true.

## Calculating time: Standard time vs. pay time

  - **Standard time**: This is considered “pure” work time, that is, the time during a work day when a worker is working on tasks.

  - **Pay time**: This is standard time (= work time) including paid breaks.

## Example 1 from the standard setup: Profile specification type Overtime

In the **Calculation parameters** form, if **Working time** is registered during a period in which the profile specification type **Overtime** is set up in the work time profile, after the time is calculated, it is included in **Standard time**, **Pay time** and **Pay overtime**.

When paid time is calculated, pay is generated from pay agreement lines in the pay agreement regarding the following wage types:

  - **Standard time** (= **Pay time**)

  - **Overtime** (= **Pay overtime**)

  - **Premiums** (If any premiums are set up in the pay agreement used to calculate the worker’s pay)

This means that when a worker works overtime, the worker receives the standard pay plus an overtime bonus plus premiums (for example, an operation- or task-related bonus, or a seniority bonus).


> [!NOTE]
> <P>Clear the <STRONG>Pay time</STRONG> check box in the <STRONG>Paid</STRONG> section in the <STRONG>Calculation parameters</STRONG> form if overtime is set up as one amount including overtime pay (and not a standard pay rate plus an overtime bonus).</P>



## Example 2 from the standard setup: Profile specification type Flex-

In the **Calculation parameters** form, if **Working time** is registered during a period in which the profile specification type **Flex-** is defined in the work time profile, the following is true. After the time is calculated, it is included in **Standard time** and **Pay time**.

When paid time is calculated, pay is generated from pay agreement lines in the pay agreement regarding the following wage types:

  - **Standard time** (= **Pay time**)

  - **Premiums** (If any premiums are set up in the pay agreement used to calculate the worker’s pay)

This means that if a worker is at work during a **Flex-** period in the worker’s profile, he or she receives standard pay plus premiums (if the worker is qualified for receiving premiums).

## Example 3 from the standard setup: Profile specification type Flex+

In the **Calculation parameters** form, if **Working time** is registered during a period in which the profile specification type **Flex+** is defined in the work time profile, the following is true. After the time is calculated, it is included in **Standard time**, **Pay time**, and **Flex+**.

When paid time is calculated, pay is generated from pay agreement lines in the pay agreement regarding the following wage types:

  - **Flex+** (If a special flex pay type is included in the pay agreement used to calculate the worker’s pay)

  - **Premiums** (If any premiums are set up in the pay agreement used to calculate the worker’s pay)


> [!NOTE]
> <P>If a worker is at work during a <STRONG>Flex+</STRONG> period in the worker’s profile, he or she does not receive standard pay or overtime pay. Also, the time is added to the worker’s flex balance.</P>



## See also

[About payroll in Time and attendance](about-payroll-in-time-and-attendance.md)

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About profile types for time and attendance registrations](about-profile-types-for-time-and-attendance-registrations.md)

[About time and attendance registrations](about-time-and-attendance-registrations.md)

[Time and attendance parameters (form)](https://technet.microsoft.com/library/aa634266\(v=ax.60\))

[Calculation parameters (form)](https://technet.microsoft.com/library/aa584600\(v=ax.60\))

  


