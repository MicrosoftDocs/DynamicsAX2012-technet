---
title: About allocation keys
TOCTitle: About allocation keys
ms:assetid: 85f6e170-7630-4d16-aff8-9c164a90201b
ms:mtpsurl: https://technet.microsoft.com/library/Aa571577(v=AX.60)
ms:contentKeyID: 44081000
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About allocation keys 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In **Manufacturing execution**, you can bundle jobs. This makes it possible to start multiple jobs at a time in the **Job registration (Job list)** form.

If you bundle jobs, you must define how the total registered time for all the jobs should be allocated to each job. You can define the allocation by selecting one of the following options in the **Bundle type** field in the **Allocation keys** form:

  - **Estimation** – Time is divided between the jobs based on the estimated time for the jobs.

  - **Jobs** – Time is divided according to total jobs bundled and how much time was spent finishing all the jobs.

  - **Net time** – Time is divided equally between the jobs that are in the bundle at any time.

  - **Real time** – Actual job time is allocated. The cost can be calculated based on the actual payroll cost.
    

    > [!NOTE]
    > <P>The <STRONG>Real time</STRONG> allocation key is available only if your company uses the payroll functionality in <STRONG>Time and attendance</STRONG>.</P>



The results of the different allocation keys are illustrated in the following examples.

## Assumptions

Three jobs in your job queue must be completed. You start the first job, and while that job is in progress, you start the second and third jobs. This makes a bundle of three jobs.

The following table shows the estimated production time for each job.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Production time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job 1</p></td>
<td><p>1 hour</p></td>
</tr>
<tr class="even">
<td><p>Job 2</p></td>
<td><p>3 hours</p></td>
</tr>
<tr class="odd">
<td><p>Job 3</p></td>
<td><p>4 hours</p></td>
</tr>
<tr class="even">
<td><p>Total</p></td>
<td><p>8 hours</p></td>
</tr>
</tbody>
</table>


The following table shows the actual work hours that are spent on each job.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Start time</p></th>
<th><p>End time</p></th>
<th><p>Bundle time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job 1</p></td>
<td><p>09:00</p></td>
<td><p>11:00</p></td>
<td><p>2 hours</p></td>
</tr>
<tr class="even">
<td><p>Job 2</p></td>
<td><p>10:00</p></td>
<td><p>13:00</p></td>
<td><p>3 hours</p></td>
</tr>
<tr class="odd">
<td><p>Job 3</p></td>
<td><p>10:00</p></td>
<td><p>15:00</p></td>
<td><p>5 hours</p></td>
</tr>
<tr class="even">
<td><p>Bundle</p></td>
<td><p>09:00</p></td>
<td><p>15:00</p></td>
<td><p>6 hours</p></td>
</tr>
</tbody>
</table>


The following sections describe the results of the calculated time for each allocation key.

## Estimation allocation key

The following table illustrates the formula for calculating allocated time. The formula is as follows:

Time per job = Total bundle time \* (Estimated job time / Total estimated time)

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Formula</p></th>
<th><p>Allocated time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job 1</p></td>
<td><p>6 * (1/8) hours</p></td>
<td><p>0.75 hour</p></td>
</tr>
<tr class="even">
<td><p>Job 2</p></td>
<td><p>6 * (3/8) hours</p></td>
<td><p>2.25 hours</p></td>
</tr>
<tr class="odd">
<td><p>Job 3</p></td>
<td><p>6 * (4/8) hours</p></td>
<td><p>3.00 hours</p></td>
</tr>
</tbody>
</table>


## Jobs allocation key

The following table illustrates the formula for calculating allocated time. The formula is as follows:

Time per job = Total bundle time / Number of jobs

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Formula</p></th>
<th><p>Allocated time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job 1</p></td>
<td><p>6/3</p></td>
<td><p>2 hours</p></td>
</tr>
<tr class="even">
<td><p>Job 2</p></td>
<td><p>6/3</p></td>
<td><p>2 hours</p></td>
</tr>
<tr class="odd">
<td><p>Job 3</p></td>
<td><p>6/3</p></td>
<td><p>2 hours</p></td>
</tr>
</tbody>
</table>


## Net time allocation key

The following table illustrates the formula for calculating allocated time. The formula is as follows:

Calculated time per reporting = Bundle time / Number of jobs

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
<th><p>09:00-10:00</p>
<p>1 hour</p></th>
<th><p>10:00-11:00</p>
<p>1 hour</p></th>
<th><p>11:00-13:00</p>
<p>2 hours</p></th>
<th><p>13:00-15:00</p>
<p>2 hours</p></th>
<th><p>Allocated time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Number of jobs in the bundle</p></td>
<td><p>1</p></td>
<td><p>3</p></td>
<td><p>2</p></td>
<td><p>1</p></td>
<td><p>N/A</p></td>
</tr>
<tr class="even">
<td><p>Job 1</p></td>
<td><p>1/1</p>
<p>= 1 hour</p></td>
<td><p>1/3</p>
<p>= 0.33 hour</p></td>
<td><p>N/A</p></td>
<td><p>N/A</p></td>
<td><p>1.33 hours</p></td>
</tr>
<tr class="odd">
<td><p>Job 2</p></td>
<td><p>N/A</p></td>
<td><p>1/3</p>
<p>= 0.33 hour</p></td>
<td><p>2/2</p>
<p>= 1 hour</p></td>
<td><p>N/A</p></td>
<td><p>1.33 hours</p></td>
</tr>
<tr class="even">
<td><p>Job 3</p></td>
<td><p>N/A</p></td>
<td><p>1/3</p>
<p>= 0.33 hour</p></td>
<td><p>2/2</p>
<p>= 1 hour</p></td>
<td><p>2/1</p>
<p>= 2 hours</p></td>
<td><p>3.33 hours</p></td>
</tr>
</tbody>
</table>


## Real time allocation key

If you want to allow for production costs to be calculated based on real costs, you must clear the **Cost category** check box in the **Production parameters** form. Click **Production control** \> **Setup** \> **Manufacturing execution** \> **Production parameters**. Click **General**, and then clear the **Cost category** check box.

The following table illustrates the formula for calculating allocated time. The formula is as follows:

Actual time per job = Actual time in bundle

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Actual time</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job 1</p></td>
<td><p>2 hours</p></td>
</tr>
<tr class="even">
<td><p>Job 2</p></td>
<td><p>3 hours</p></td>
</tr>
<tr class="odd">
<td><p>Job 3</p></td>
<td><p>5 hours</p></td>
</tr>
</tbody>
</table>


Consider the three jobs performed by a worker who has an hourly wage of USD 12.00. No overtime bonus or premium was earned in the time that was spent on the jobs.

The worker worked on the three bundled jobs for a total of 6 hours. The salary cost is then 6 \* USD 12.00 = USD 72.00.

When you use real time allocation, the cost per hour is recalculated by using the factor from the **Net time** formula. The actual time that was spent on each job is then transferred with the corrected cost price per hour.

In the example, six hours are spent although 10 hours were allocated.

The following table illustrates the formula for calculating cost. The formula is as follows:

Cost per hour = (Total bundle time per job (Net time) / Actual time per job) \* Standard cost price per hour

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job</p></th>
<th><p>Calculation of corrected cost per hour</p></th>
<th><p>Corrected cost per hour</p></th>
<th><p>Allocated time</p></th>
<th><p>Total cost of job</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Job 1</p></td>
<td><p>(1.33/2) * USD 12.00</p></td>
<td><p>USD 8.00</p></td>
<td><p>2 hours</p></td>
<td><p>USD 16.00</p></td>
</tr>
<tr class="even">
<td><p>Job 2</p></td>
<td><p>(1.33/3) * USD 12.00</p></td>
<td><p>USD 5.33</p></td>
<td><p>3 hours</p></td>
<td><p>USD 16.00</p></td>
</tr>
<tr class="odd">
<td><p>Job 3</p></td>
<td><p>(3.33/5) * USD 12.00</p></td>
<td><p>USD 8.00</p></td>
<td><p>5 hours</p></td>
<td><p>USD 40.00</p></td>
</tr>
</tbody>
</table>


The corrected cost per hour and the job time are posted in a production journal.


> [!NOTE]
> <P>If you select the <STRONG>Cost category</STRONG> check box in the <STRONG>General</STRONG> area in the <STRONG>Production parameters</STRONG> form, the actual time for each job is transferred to a production journal, where the cost is applied to the cost category of the specific job.</P>



## See also

[Key tasks: Set up manufacturing execution](key-tasks-set-up-manufacturing-execution.md)

[About production parameters in Manufacturing execution](about-production-parameters-in-manufacturing-execution.md)

  


