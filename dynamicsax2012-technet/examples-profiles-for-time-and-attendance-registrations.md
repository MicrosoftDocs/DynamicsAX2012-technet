---
title: 'Examples: Profiles for time and attendance registrations'
TOCTitle: 'Examples: Profiles for time and attendance registrations'
ms:assetid: 9719e42a-cf11-497e-a65c-92cadf5f0fd7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498430(v=AX.60)
ms:contentKeyID: 36058667
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Examples: Profiles for time and attendance registrations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following sections provide examples of work time profiles for different workers and shifts. All examples are based on the standard setup of **Calculation parameters**, which is used to calculate time registrations and pay time, based on profile types. For more information, see [About parameters for calculations](about-parameters-for-calculations.md).

Set up time registration profiles in the **Profile** form. Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time profiles** \> **Profiles**.

Set up calculation parameters in the **Calculation parameters** form. Click **Human resources** \> **Setup** \> **Time and attendance** \> **Calculation parameters**.

## Day shift profile

This is an example of a general profile that can be used for a day shift in a two-shift or three-shift rotation schedule, or for office workers who do not work in shifts.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value</p></th>
<th><p>Field</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>New 24-hour period</strong>:</p></td>
<td><p>00:00:00</p></td>
<td><p><strong>Overtime / flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
<tr class="even">
<td><p><strong>24-hour period start</strong>:</p></td>
<td><p><strong>This day</strong></p></td>
<td><p><strong>Max. flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Profile type</strong></p></th>
<th><p><strong>Start</strong></p></th>
<th><p><strong>End</strong></p></th>
<th><p><strong>Tolerance before start</strong></p></th>
<th><p><strong>Tolerance after start</strong></p></th>
<th><p><strong>Tolerance before end</strong></p></th>
<th><p><strong>Tolerance after end</strong></p></th>
<th><p><strong>Switch code</strong></p></th>
<th><p><strong>Secondary</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>00:00</p></td>
<td><p>07:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock in</strong></p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
<td><p>15</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>2</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>07:00</p></td>
<td><p>11:30</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Break</strong></p></td>
<td><p>11:30</p></td>
<td><p>12:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p><strong>Overtime</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>12:00</p></td>
<td><p>15:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock out</strong></p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>15</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>15:00</p></td>
<td><p>00:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


Based on this example profile:

  - Clock-in between 06:45 and 07:00 will not result in overtime payment because of the tolerance (**Tolerance before start**).

  - Clock-in between 07:00 and 07:02 will not result in a reduction in pay because of the tolerance (**Tolerance after end**).

  - Clock-out between 15:00 and 15:15 will not result in overtime payment because of the tolerance (**Tolerance after end**).

  - If the break between 11:30 and 12:00 is cancelled, that time is considered to be overtime.

## Flextime profile

This profile can be used for workers who work flexible hours.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value</p></th>
<th><p>Field</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>New 24-hour period</strong>:</p></td>
<td><p>00:00:00</p></td>
<td><p><strong>Overtime / flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
<tr class="even">
<td><p><strong>24-hour period start</strong>:</p></td>
<td><p><strong>This day</strong></p></td>
<td><p><strong>Max. flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Profile type</strong></p></th>
<th><p><strong>Start</strong></p></th>
<th><p><strong>End</strong></p></th>
<th><p><strong>Tolerance before start</strong></p></th>
<th><p><strong>Tolerance after start</strong></p></th>
<th><p><strong>Tolerance before end</strong></p></th>
<th><p><strong>Tolerance after end</strong></p></th>
<th><p><strong>Switch code</strong></p></th>
<th><p><strong>Secondary</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>00:00</p></td>
<td><p>07:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Flex+</strong></p></td>
<td><p>07:00</p></td>
<td><p>08:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>O1</p></td>
<td><p><strong>Overtime</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Clock in</strong></p></td>
<td><p>08:00</p></td>
<td><p>08:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Flex-</strong></p></td>
<td><p>08:00</p></td>
<td><p>09:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Paid break</strong></p></td>
<td><p>09:00</p></td>
<td><p>09:15</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Standard time</strong></p></td>
<td><p>09:15</p></td>
<td><p>11:30</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Break</strong></p></td>
<td><p>11:30</p></td>
<td><p>12:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p><strong>Flex+</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Standard time</strong></p></td>
<td><p>12:00</p></td>
<td><p>13:45</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Break</strong></p></td>
<td><p>13:45</p></td>
<td><p>14:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Standard time</strong></p></td>
<td><p>14:00</p></td>
<td><p>15:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Flex-</strong></p></td>
<td><p>15:00</p></td>
<td><p>16:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock out</strong></p></td>
<td><p>16:00</p></td>
<td><p>16:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Flex+</strong></p></td>
<td><p>16:00</p></td>
<td><p>17:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>O2</p></td>
<td><p><strong>Overtime</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Overtime</strong></p></td>
<td><p>17:00</p></td>
<td><p>00:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


Based on this example profile:

  - There is a two-hour flex zone in the morning and a two-hour flex zone in the afternoon.

  - Workers can clock in between 07:00 and 09:00 and clock out between 15:00 and 17:00 and still get paid for a full work day. Any difference between paid time and actual work time will cause an adjustment to the flex balance.

  - If the switch code O1 is registered, working between 06:00 and 07:00 is considered to be overtime.

  - If the switch code O2 is registered, working between 16:00 and 17:00 is considered to be overtime.

  - If the break between 11:30 and 12:00 is cancelled, that time is added to the flex balance.

## Evening shift profile

This profile is an example of an evening shift.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value</p></th>
<th><p>Field</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>New 24-hour period</strong>:</p></td>
<td><p>00:00:00</p></td>
<td><p><strong>Overtime / flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
<tr class="even">
<td><p><strong>24-hour period start</strong>:</p></td>
<td><p><strong>This day</strong></p></td>
<td><p><strong>Max. flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Profile type</strong></p></th>
<th><p><strong>Start</strong></p></th>
<th><p><strong>End</strong></p></th>
<th><p><strong>Tolerance before start</strong></p></th>
<th><p><strong>Tolerance after start</strong></p></th>
<th><p><strong>Tolerance before end</strong></p></th>
<th><p><strong>Tolerance after end</strong></p></th>
<th><p><strong>Switch code</strong></p></th>
<th><p><strong>Secondary</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>07:00</p></td>
<td><p>15:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock in</strong></p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p>15</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>2</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>15:00</p></td>
<td><p>18:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Break</strong></p></td>
<td><p>18:00</p></td>
<td><p>18:30</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p><strong>Overtime</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>18:30</p></td>
<td><p>23:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock out</strong></p></td>
<td><p>23:00</p></td>
<td><p>23:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>15</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>23:00</p></td>
<td><p>07:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


Based on this example profile:

  - Clock-in between 14:45 and 15:00 will not result in overtime payment because of the tolerance (**Tolerance before start**).

  - Clock-in between 15:00 and 15:02 will not result in a reduction in pay because of the tolerance (**Tolerance after end**).

  - Clock out between 23:00 and 23:15 will not result in overtime payment because of the tolerance (**Tolerance after end**).

  - If the break between 18:00 and 18:30 is cancelled, that time is considered to be overtime.

## Night shift profile

This profile is an example of a shift that works across midnight.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value</p></th>
<th><p>Field</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>New 24-hour period</strong>:</p></td>
<td><p>20:00:00</p></td>
<td><p><strong>Overtime / flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
<tr class="even">
<td><p><strong>24-hour period start</strong>:</p></td>
<td><p><strong>Previous day</strong></p></td>
<td><p><strong>Max. flex limit</strong>:</p></td>
<td><p>00:00:00</p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Profile type</strong></p></th>
<th><p><strong>Start</strong></p></th>
<th><p><strong>End</strong></p></th>
<th><p><strong>Tolerance before start</strong></p></th>
<th><p><strong>Tolerance after start</strong></p></th>
<th><p><strong>Tolerance before end</strong></p></th>
<th><p><strong>Tolerance after end</strong></p></th>
<th><p><strong>Switch code</strong></p></th>
<th><p><strong>Secondary</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>20:00</p></td>
<td><p>23:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock in</strong></p></td>
<td><p>23:00</p></td>
<td><p>23:00</p></td>
<td><p>15</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>2</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>23:00</p></td>
<td><p>03:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Break</strong></p></td>
<td><p>03:00</p></td>
<td><p>03:30</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p><strong>Overtime</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Standard time</strong></p></td>
<td><p>03:30</p></td>
<td><p>07:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Clock out</strong></p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>15</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>07:00</p></td>
<td><p>20:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


Based on this example profile:

  - The **Previous day** selection in the **24-hour period start** box indicates that the profile starts before midnight. If this is the profile for Monday, clock-in is expected at 22:00 on Sunday evening.

  - Clock-in after 20:00 (**New 24-hour period** field) means that the profile for the following day will be used.

  - Clock-in between 22:45 and 23:00 will not result in overtime payment because of the tolerance (**Tolerance before start**).

  - Clock-in between 23:00 and 23:02 will not result in a reduction in pay because of the tolerance (**Tolerance after end**).

  - Clock-out between 07:00 and 07:15 will not result in overtime payment because of the tolerance (**Tolerance after end**).

  - If the break between 03:00 and 03:30 is cancelled, that time is considered to be overtime.


> [!NOTE]
> <P>The <STRONG>Push</STRONG> check box is relevant if a night shift profile crosses midnight <STRONG>and</STRONG> the profile date for the profile is the date of clock-in. In the night shift profile example above, the profile date is the date of clock-out because <STRONG>Previous day</STRONG> is selected in the <STRONG>24-hour period start</STRONG> field.</P>
> <P>Example using <STRONG>Push</STRONG> based on the night shift profile above:</P>
> <UL>
> <LI>
> <P>In the <STRONG>New 24-hour period</STRONG> field, insert the time 02:00:00.</P>
> <LI>
> <P>Select the <STRONG>Push</STRONG> check box.</P>
> <LI>
> <P>In the <STRONG>24-hour period start</STRONG> field, select <STRONG>This day</STRONG>.</P></LI></UL>



## Flex profile with no fixed clock-in time

If some workers have no fixed clock-in time, you can set up a profile like this one. In the example, workers are expected to work 7.5 hours a day. But they can decide themselves at which time during the day they will be at work.

They will generate flexible hours for a maximum of 2.0 hours per work day if they work more than 7.5 hours. Work time exceeding 9.5 hours a day will be converted into overtime.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value</p></th>
<th><p>Field</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>New 24-hour period</strong>:</p></td>
<td><p>00:00:00</p></td>
<td><p><strong>Overtime / flex limit</strong>:</p></td>
<td><p>07:30:00</p></td>
</tr>
<tr class="even">
<td><p><strong>24-hour period start</strong>:</p></td>
<td><p><strong>This day</strong></p></td>
<td><p><strong>Max. flex limit</strong>:</p></td>
<td><p>02:00:00</p></td>
</tr>
</tbody>
</table>


<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Profile type</strong></p></th>
<th><p><strong>Start</strong></p></th>
<th><p><strong>End</strong></p></th>
<th><p><strong>Tolerance before start</strong></p></th>
<th><p><strong>Tolerance after start</strong></p></th>
<th><p><strong>Tolerance before end</strong></p></th>
<th><p><strong>Tolerance after end</strong></p></th>
<th><p><strong>Switch code</strong></p></th>
<th><p><strong>Secondary</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>00:00</p></td>
<td><p>23:59</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Overtime</strong></p></td>
<td><p>23:59</p></td>
<td><p>22:00</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


Based on this example profile:

  - If a worker registers between 7.5 and 9.5 work hours on a day, 7.5 hours will be registered as standard time, and the rest of the work time will be added to the flex balance.

  - If a worker registers more than 9.5 hours on a day, 7.5 hours will be registered as standard time, 2.0 hours will be added to the flex balance, and the rest will be registered as overtime.

  - Breaks during the work day must be registered by the worker.

  - The reason for including a second line displaying **Overtime** from 23:59 to 22:00 (the following day) is to allow workers to work through the night on the same profile date.

  - If the worker works less than 7.5 hours a day, absence must be registered; this can be done automatically.

## Insert flex- or absence registration automatically

You can set up parameters to insert an absence code automatically in a flex profile with no fixed clock-in time:

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Time and attendance parameters**.

2.  On the **General** tab, in the **Auto insert flex- / absence** field, select an absence code.


> [!NOTE]
> <P>The selected absence code will be inserted automatically during calculation of the worker’s registrations.</P>



## See also

[About profiles for time and attendance registrations](about-profiles-for-time-and-attendance-registrations.md)

[About profile types for time and attendance registrations](about-profile-types-for-time-and-attendance-registrations.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

