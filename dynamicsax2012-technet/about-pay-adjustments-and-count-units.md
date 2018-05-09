---
title: About pay adjustments and count units
TOCTitle: About pay adjustments and count units
ms:assetid: 5ee429f8-d026-41a3-a6b4-d6619ef6d233
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa549109(v=AX.60)
ms:contentKeyID: 36057584
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About pay adjustments and count units 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Pay can be calculated daily by using time and attendance. Count units and pay adjustments are additional pay-related features that can be applied to adjust workers’ registrations during approval of registrations.

The count units are typically applied to add certain premiums to a worker’s pay. For example, a count unit might be applied if a worker receives a bonus when working more than 10 hours on a specific process during a week.

The pay adjustments are typically applied when pay must be deducted. For example, a pay adjustment might be applied if a worker receives overtime pay on one day but is late for work the following day.

## Count unit example

A company has a specific operation that requires a high level of skill or special training. Because of the special skill requirement, workers receive a bonus when they work on that operation.

However, the operation is very strenuous. Therefore, to make sure that the operation is not performed by the same worker all week, the bonus is only paid for the first 10 hours each week. When the worker has worked 10 hours on the operation during the week, the incentive bonus is removed.

## Pay adjustment example

A company only pays overtime if a worker has worked a minimum of 40 hours of standard time during week.

Working hours are expected to be eight hours a day, Monday through Friday. If a worker works overtime at the beginning of the week, but has not reached the level of 40 hours of standard work time by the end of the week, the overtime should be reduced.

Additionally, weeks that contain holidays have a reduced overtime limit. Therefore, if the typical work day is eight hours, a full holiday will reduce the overtime limit of the week by eight hours.

The company uses the following pay types:

  - Pay type 1201 is paid for all standard work hours.

  - Pay type 1301 is paid for overtime.

To handle the 40-hour example, you can set up a pay adjustment. The pay adjustment should be made for calculated overtime if the standard time registered for the pay period does not reach the expected standard time for that pay period.

In this example, the calculation of the pay adjustment is based on:

  - The calculated expected standard time for the week. The expected standard time for a day is the time between the planned clock-in and clock-out time, as set up in the work time profile that is used for time calculation on the given day. This is also referred to as norm time.

  - The realized paid standard time. The realized paid standard time for a day is all the paid hours minus the overtime hours.

The number of hours that should reduce possible overtime is any difference between the paid standard time and the expected standard time of the week.

## Expected work hours

The following table shows the expected working hours/standard time for the week.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Monday</p></th>
<th><p>Tuesday</p></th>
<th><p>Wednesday</p></th>
<th><p>Thursday</p></th>
<th><p>Friday</p></th>
<th><p>Total hours</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expected clock-in time</p></td>
<td><p>7:00</p></td>
<td><p>7:00</p></td>
<td><p>7:00</p></td>
<td><p>7:00</p></td>
<td><p>7:00</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="even">
<td><p>Expected clock-out time</p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="odd">
<td><p>Expected paid hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>40 hours</p></td>
</tr>
</tbody>
</table>


## Actual work hours

The following table shows an example of actual work hours for a specific worker.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Monday</p></th>
<th><p>Tuesday</p></th>
<th><p>Wednesday</p></th>
<th><p>Thursday</p></th>
<th><p>Friday</p></th>
<th><p>Total hours</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Actual clock-in time</p></td>
<td><p>7:00</p></td>
<td><p>7:00</p></td>
<td><p>9:00</p></td>
<td><p>7:00</p></td>
<td><p>9:00</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="even">
<td><p>Actual clock-out time</p></td>
<td><p>18:00</p></td>
<td><p>15:00</p></td>
<td><p>15:00</p></td>
<td><p>18:00</p></td>
<td><p>15:00</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="odd">
<td><p>Absence</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>2 hours</p></td>
<td><p>0</p></td>
<td><p>2 hours</p></td>
<td><p>4</p></td>
</tr>
<tr class="even">
<td><p>Total paid hours</p></td>
<td><p>11 hours</p></td>
<td><p>8 hours</p></td>
<td><p>6 hours</p></td>
<td><p>11 hours</p></td>
<td><p>6 hours</p></td>
<td><p>42 hours</p></td>
</tr>
<tr class="odd">
<td><p>Overtime hours</p></td>
<td><p>3 hours</p></td>
<td><p>0</p></td>
<td><p>0</p></td>
<td><p>3 hours</p></td>
<td><p>0</p></td>
<td><p>6 hours</p></td>
</tr>
</tbody>
</table>


## Calculated overtime pay without adjustment

Payroll transactions are calculated every day. If no adjustment is set up, the payroll transactions are calculated as shown below.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Monday</p></th>
<th><p>Thursday</p></th>
<th><p>Total hours</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Overtime – pay type 1301</p></td>
<td><p>3 hours</p></td>
<td><p>3 hours</p></td>
<td><p>6</p></td>
</tr>
</tbody>
</table>


However, the previous calculation does not correspond with the company rules for overtime payment.

## Calculated overtime pay with adjustment

After a pay adjustment is made, overtime pay for the week is calculated as shown below.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Monday</p></th>
<th><p>Tuesday</p></th>
<th><p>Wednesday</p></th>
<th><p>Thursday</p></th>
<th><p>Friday</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accumulated overtime – pay type 1301</p></td>
<td><p>3 hours</p></td>
<td><p>3 hours</p></td>
<td><p>1 hour</p></td>
<td><p>4 hours</p></td>
<td><p>2 hours</p></td>
</tr>
</tbody>
</table>


  - **Monday** - The worker has three hours of overtime.

  - **Tuesday** - No deduction in overtime.

  - **Wednesday** - Two hours of overtime are deducted because of absence.

  - **Thursday** - Three hours of overtime are added.

  - **Friday** - Two hours of overtime are deducted because of absence.

When the work week is calculated, the worker receives a total of two hours of overtime pay.

## See also

[Example of a pay adjustment for time and attendance](example-of-a-pay-adjustment-for-time-and-attendance.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

