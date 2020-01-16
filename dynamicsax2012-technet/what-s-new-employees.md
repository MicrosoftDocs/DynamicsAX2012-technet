---
title: "What's new: Employees"
TOCTitle: Employees
ms:assetid: 375461dc-f3ea-4568-9be2-e34b1d821f16
ms:mtpsurl: https://technet.microsoft.com/library/Dn507090(v=AX.60)
ms:contentKeyID: 59623182
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Employees 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Employees are now a type of worker. A worker can be a person who is either a contractor or an employee. Multiple tables throughout Microsoft Dynamics AX 2012 have been renamed or changed to reflect this change in the conceptual model.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required</p></td>
<td><p>Conditionally required. If you are using this feature in an earlier version of Microsoft Dynamics AX, significant changes have been made, and you must review this topic.</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Human resources</p>
<p>For information about changes to other Human resources features, see <a href="what-s-new-human-resources-features.md">What's new: Human resources features</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

Enhanced effective date patterns have been added to track past, current, and future transactions that are related to the worker record. You can also hire, transfer, and terminate workers more easily now. Additionally, you can more easily move a worker’s employment records from one legal entity to another and track a worker’s employment history.

## Special considerations

Employees and contractors are now shared entities. The worker table (HcmWorker) is no longer assigned to a specific data area ID. You can use the employment record (HcmEmployment) to assign a worker to multiple legal entities. You can also use XDS security policies to mimic containment of the worker data by legal entity.

The following information must also be considered:

  - You can use security roles to provide self-service capabilities for workers through Enterprise Portal for Microsoft Dynamics AX.

  - Worker status is now derived from employment status.

  - Work centers are no longer part of the Employee table.

  - Competencies are associated with the person, not with the virtual network. Additionally, competencies are shared across legal entities.

  - The **Delete personal information** option has been removed from the Employee Wizard.

  - You can still assign absence and compensation functionality to a data area ID. Therefore, the absence and compensation functionality is contained through the current legal entity context. When you modify absence and compensation information for a worker, you must be logged on to the legal entity that you want to record the absence and compensation records in.

## Comparison with Microsoft Dynamics AX 2009

This feature has changed considerably since AX 2009. AX 2012 includes changes to the following areas:

  - Human resources

  - Signature authority

## Human resources

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Hire applicants as workers.</p></td>
<td><p>Multiple steps were required to complete the hiring process.</p></td>
<td><p>Fewer manual steps are required to hire an applicant.</p></td>
<td><p>You can be sure that new hires are correctly onboarded into the organization.</p></td>
</tr>
<tr class="even">
<td><p>Terminate a worker’s employment.</p></td>
<td><p>Multiple steps were required to complete the termination process.</p></td>
<td><p>Fewer manual steps are required to terminate a worker’s employment.</p></td>
<td><p>There might be fewer errors in reporting, compensation, and payroll after a worker’s employment is terminated.</p></td>
</tr>
<tr class="odd">
<td><p>View an employee’s history.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>Users can track past, current, and future transactions that are related to a worker’s employment history.</p></td>
<td><p>A comprehensive historical record of the worker’s employment history is displayed.</p></td>
</tr>
<tr class="even">
<td><p>Transfer a worker to a new position.</p></td>
<td><p>Multiple steps were required to complete the transfer process.</p></td>
<td><p>The process for transferring workers from one position to another is streamlined, and the transfer history is recorded.</p></td>
<td><p>You can be sure that workers are correctly transferred, and that hiring managers have the information that they require to manage this step of the transition process.</p></td>
</tr>
<tr class="odd">
<td><p>Move a worker’s employment from one legal entity to another legal entity.</p></td>
<td><p>Multiple steps were required to move an employee from one legal entity to another legal entity.</p></td>
<td><p>Fewer manual steps are required to move a worker from one legal entity to another legal entity.</p></td>
<td><p>This process is more intuitive, and less manual work is required to move a worker’s employment record from one legal entity to another legal entity.</p></td>
</tr>
<tr class="even">
<td><p>View human resources reports that contain information from multiple legal entities.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>You can view human resources reports that include information from multiple legal entities.</p></td>
<td><p>You do not have to log on to a different legal entity to view reports for that legal entity.</p></td>
</tr>
</tbody>
</table>


## Signature authority

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Grant spending authority to employees for business expenses. Grant approval authority to managers, so that they can approve business expenses.</p></td>
<td><p>Basic support was provided for spending and approval limits.</p></td>
<td><p>Advanced configuration and administration capabilities have been added.</p></td>
<td><p>Companies can enforce corporate spending and approval limits at a more detailed level.</p></td>
</tr>
<tr class="even">
<td><p>Submit self-service requests for spending and approval limits.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>Employees can request a signing limit for business expenses, and managers can request an approval limit via the employee portal.</p></td>
<td><p>The process for requesting and approving spending and approval limits by using workflow is automated and simplified.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about employees and the Human Resources Framework, see the white paper [Implementing and Updating the Human Resources Framework for Microsoft Dynamics AX 2012 Applications](http://go.microsoft.com/fwlink/?linkid=213128%26clcid=0x409).

  


