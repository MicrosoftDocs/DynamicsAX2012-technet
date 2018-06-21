---
title: Example of a pay adjustment for time and attendance
TOCTitle: Example of a pay adjustment for time and attendance
ms:assetid: f5b2960f-f966-4354-bc19-0c3df5775e10
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551648(v=AX.60)
ms:contentKeyID: 36060004
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Example of a pay adjustment for time and attendance [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides an example of using the pay adjustment feature in time and attendance.

## Rules for overtime pay

Suppose that the overtime regulations for a legal entity state that overtime will only be paid if the worker has worked a minimum of 40 hours of standard time per week.

If a worker has worked overtime at the start of the week, the overtime is reduced if the worker has not reached 40 hours of standard time at the end of the week, and the missing standard work hours are defined as absence without a valid reason.

If the missing standard work hours are caused by absence with a valid reason, no reduction is made in the overtime.

## Setup of overtime payment

The following table shows the pay types that the legal entity creates.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Pay type</strong></p></th>
<th><p>Paid for</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1201</p></td>
<td><p>All standard work hours.</p></td>
</tr>
<tr class="even">
<td><p>1301</p></td>
<td><p>The first two hours of overtime per day.</p></td>
</tr>
</tbody>
</table>


To make sure that the workers receive the correct amount of overtime pay, a pay adjustment rule can be set up:

Paid overtime will be reduced if the actual number of standard work hours for the pay period is less than the expected number of standard work hours.

The calculation of the pay adjustment is based on the following information:

  - The calculated expected standard time for the week.


> [!NOTE]
> <P>The expected standard time for a day is the time between the planned clock-in time and clock-out time, as set up in the profile. For more information, see <A href="about-profiles-for-time-and-attendance-registrations.md">About profiles for time and attendance registrations</A>.</P>



  - The realized paid standard time.


> [!NOTE]
> <P>The realized paid standard time for a day is all the paid hours minus the overtime hours.</P>



The number of earned overtime hours is reduced with the difference, if any, in the number of paid standard time work hours compared to the number of expected standard time work hours for the period.

The following table displays the expected clock-in and clock-out for a worker, the actual clock-in and clock-out, and the calculation of overtime.


> [!NOTE]
> <P>You can update the calculation parameters so that absence is considered to be payable time. Click <STRONG>Human resources</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Time and attendance</STRONG> &gt; <STRONG>Calculation parameters</STRONG>.</P>



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
<th><p>Mon</p></th>
<th><p>Tue</p></th>
<th><p>Wed</p></th>
<th><p>Thu</p></th>
<th><p>Fri</p></th>
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Expected clock-in time</p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
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
<td><p>Expected paid time</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>8 hours</p></td>
<td><p>40 hours</p></td>
</tr>
<tr class="even">
<td><p>Actual clock-in time</p></td>
<td><p>07:00</p></td>
<td><p>07:00</p></td>
<td><p>09:00</p></td>
<td><p>07:00</p></td>
<td><p>09:00</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="odd">
<td><p>Actual clock-out time</p></td>
<td><p>18:00</p></td>
<td><p>14:00</p></td>
<td><p>15:00</p></td>
<td><p>18:00</p></td>
<td><p>15:00</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="even">
<td><p>Paid (valid) absence</p></td>
<td><p>0 hours</p></td>
<td><p>1 hour</p></td>
<td><p>0 hours</p></td>
<td><p>0 hours</p></td>
<td><p>0 hours</p></td>
<td><p>1 hours</p></td>
</tr>
<tr class="odd">
<td><p>Not paid (not valid) absence</p></td>
<td><p>0 hours</p></td>
<td><p>0 hours</p></td>
<td><p>2 hours</p></td>
<td><p>0 hours</p></td>
<td><p>2 hours</p></td>
<td><p>4 hours</p></td>
</tr>
<tr class="even">
<td><p>Total paid time</p></td>
<td><p>11 hours</p></td>
<td><p>8 hours</p></td>
<td><p>6 hours</p></td>
<td><p>11 hours</p></td>
<td><p>6 hours</p></td>
<td><p>42 hours</p></td>
</tr>
<tr class="odd">
<td><p><strong>Overtime</strong></p></td>
<td><p>3 hours</p></td>
<td><p>0 hours</p></td>
<td><p>0 hours</p></td>
<td><p>3 hours</p></td>
<td><p>0 hours</p></td>
<td><p>6 hours</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Settings for the absence group will determine whether the absence is valid. If absence time is not considered valid, select the <STRONG>Deduct overtime</STRONG> check box in the <STRONG>Absence groups</STRONG> form. Click <STRONG>Human resources</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Absence</STRONG> &gt; <STRONG>Absence groups</STRONG>.</P>



## Specification of payroll transactions before pay adjustment

The following table shows how payroll transactions calculated for Monday and Thursday, according to the rules specified previously for paying standard time and overtime.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>Monday</p></th>
<th><p>Thursday</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Paid overtime <strong>Pay type</strong> 1301</p></td>
<td><p>3 hours</p></td>
<td><p>3 hours</p></td>
</tr>
</tbody>
</table>


The total number of paid hours for the week is 42, of which 6 hours are overtime.

The paid standard time for the week is 40, so the overtime should be 42 minus 40 = 2 hours.

The four hours of overtime reducing absence must reduce the paid overtime of the week. You can enable this by setting up a **Pay adjustment**.

## Set up a pay adjustment

1.  Click **Human resources** \> **Setup** \> **Time and attendance** \> **Payroll** \> **Pay agreements**.

2.  Select the pay agreement to make the adjustment to, click the **Pay adjustment** button, and set up the following information:
    
      - In the **Base** field, select **Pay time**.
    
      - Leave the **Pay type** field empty.
    
      - In the **Criteria** field, select **\< Normtime**.
    
      - In the **Adjustment method** field, select **Period**.
    
      - Select the **Active** check box.

3.  Click **Pay periods**, and select or create a period of one week.

4.  Click **Adjustment pay types**, and select **Pay type** 1301.

## Specification of payroll transactions after pay adjustment

After the pay adjustment has been set up the necessary adjustments will be made daily when workers’ registrations are approved and transferred. For more information about approving and transferring registrations, see [About calculating, approving and transferring registrations](about-calculating-approving-and-transferring-registrations.md).

The following table shows how corrections will be made to the payroll transactions.

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
<th><p>Total</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Paid <strong>Overtime</strong> before adjustment</p></td>
<td><p>+ 3 hours</p></td>
<td><p>+ 3 hours</p></td>
<td><p>+ 6 hours</p></td>
</tr>
<tr class="even">
<td><p>Adjustment <strong>Pay type</strong> 1301</p></td>
<td><p>- 3 hours</p></td>
<td><p>- 1 hours</p></td>
<td><p>- 4 hours</p></td>
</tr>
<tr class="odd">
<td><p>Paid <strong>Overtime</strong> after adjustment</p></td>
<td><p>0 hour</p></td>
<td><p>+ 2 hours</p></td>
<td><p>+ 2 hours.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>Although the overtime that reduces the absence occurred on Wednesday and Friday, the adjustments are shown beginning on the first day of the selected pay period.</P>



## See also

[About pay adjustments and count units](about-pay-adjustments-and-count-units.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

