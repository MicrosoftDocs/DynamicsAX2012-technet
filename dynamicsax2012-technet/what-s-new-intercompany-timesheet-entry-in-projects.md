---
title: "What's new: Intercompany timesheet entry in projects"
TOCTitle: Intercompany timesheet entry in projects
ms:assetid: 2bf512d7-cf04-4784-a46d-61be57f059d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527122(v=AX.60)
ms:contentKeyID: 59623252
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Intercompany timesheet entry in projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

In Microsoft Dynamics AX 2012 Feature Pack, an organization can allow a worker in one legal entity to enter hours that are worked for a project that is managed in a different legal entity, without requiring that the worker switch company data sets.

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
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Feature areas affected</p></td>
<td><p>Project management and accounting</p>
<p>Human resources</p>
<p>Home (Timesheets)</p></td>
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

After AX 2012 Feature Pack is installed, a legal entity can perform the following tasks:

  - In the **Project management and accounting parameters** form, enable the functionality for intercompany timesheets.

  - In the **Transfer price (hour)** form, specify the hourly prices that the legal entity charges related legal entities for loaned workers.

  - In the **Sales price (hour)** form, specify the hourly prices that the legal entity charges customers for borrowed workers.

  - In the **Worker/project validation groups** and **Worker/category validation groups** forms, add workers from other legal entities to the legal entity’s validation setup.

By enabling the Intercompany timesheets feature, you add the following functionality:

  - Loaned workers can submit timesheet hours for project work that they perform for the legal entity that borrows them.

  - Project managers can review and approve timesheet submissions from borrowed workers. The loaning legal entity can track the amounts that are due from the borrowing legal entity.

Additionally, the Intercompany timesheets feature adds the following two new posting types:

  - **Intercompany revenue** – The account that records intercompany revenue is used by the loaning legal entity to record revenue that it receives from the loan of resources to a borrowing legal entity.

  - **Intercompany cost** – The account that records intercompany costs is used by the loaning legal entity to record the true cost that the legal entity incurs by loaning resources. An intercompany timesheet for a loaning legal entity is posted to an intercompany cost account that is offset by a payroll allocation account. By default, the financial dimensions from the worker’s profile are added to the posting entry.

## Special considerations

The invoice for intercompany time that the loaning legal entity creates cannot be sent to the borrowing legal entity through the regular accounts payable process. (In this case, the borrowing legal entity’s account is handled in the same manner as any other vendor account). Instead, the due-to and due-from amounts are recorded in ledger accounts. Based on this information, the borrowing legal entity can determine how much to pay the loaning legal entity. After the loaning legal entity settles those payments against the ledger entries, the loaning legal entity can determine which hours have been paid for.

Because of the introduction of the Intercompany timesheets feature in AX 2012 Feature Pack, the posting of timesheets is handled by the accounting framework that was introduced in AX 2012. Therefore, hour journals are no longer used to summarize subledger entries or any subsequent project transactions are that are related to timesheets. Additionally, the **Default posting level** attribute that was specific to Project management and accounting has been deprecated. If any customized solutions have been built on the timesheet functionality in AX 2012, you might have to update these solutions for AX 2012 to account for this change, even if you do not intend to take advantage of the Intercompany timesheets feature.

## Comparison with Microsoft Dynamics AX 2009

Intercompany timesheet functionality is new in AX 2012 and has changes to the following areas:

  - Hourly transfer prices and sales prices

  - Validation groups

  - Timesheet submission and approval

  - Recording of revenue and costs

## Hourly transfer prices and sales prices

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
<td><p>Specify hourly prices for workers who are loaned to a related legal entity.</p></td>
<td><p>Not available</p></td>
<td><p>Project management and accounting supports the hourly transfer process. Project management and accounting stores transfer prices for workers who work on projects that are run by related legal entities. You can create transfer prices for any combination of effective date, worker, project, category, and borrowing legal entity.</p></td>
<td><p>Borrowing legal entities are charged the correct amount for the hours that a worker from another legal entity contributes to a project.</p></td>
</tr>
<tr class="even">
<td><p>Specify hourly sales prices for borrowed workers who are assigned to a customer project.</p></td>
<td><p>Not available</p></td>
<td><p>Hourly sales prices can be assigned for workers in your own legal entity and related legal entities.</p></td>
<td><p>Sales prices for borrowed workers can be specified in your legal entity’s records in Microsoft Dynamics AX.</p></td>
</tr>
</tbody>
</table>


## Validation groups

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
<td><p>Control which projects and categories a worker can be associated with.</p></td>
<td><p>Transactions cannot be entered into hour journals for projects and categories that a worker has not been validated for. Hour transactions can be entered only for projects in the worker’s legal entity.</p></td>
<td><p>Workers can enter hours in timesheets, and can enter these hours not only in journals, but also for projects and categories that the workers have been validated for. You can add workers who are borrowed from another legal entity to validation groups in your legal entity’s records.</p></td>
<td><p>Workers can select projects that are managed in their own legal entity, and also in other legal entities for which they have been validated for work.</p></td>
</tr>
</tbody>
</table>


## Timesheet submission and approval

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
<td><p>Workers can submit timesheets, and project managers can review and approve timesheets</p></td>
<td><p>Not available</p></td>
<td><p>Workers can submit hours for project work in their own legal entity. Additionally, workers can submit hours for work that they did for legal entities that borrowed them.</p>
<p>Project managers can review timesheet submissions for work that was done by workers in their own legal entity and by workers that were borrowed from related legal entities.</p></td>
<td><p>A worker who is employed by one legal entity can enter timesheet hours for work that was performed on projects in a different legal entity, without having to be employed by the legal entity that is managing the project. Project managers do not have to log on to multiple company accounts in Microsoft Dynamics AX to submit and review timesheet hours for intercompany project work.</p></td>
</tr>
</tbody>
</table>


## Recording of revenue and costs

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
<td><p>Specify the account in which to record revenue that is received from the loan of a worker to another legal entity.</p></td>
<td><p>Not available</p></td>
<td><p>The new <strong>Intercompany revenue</strong> posting type is available in the <strong>Project groups</strong> form.</p></td>
<td><p>A loaning legal entity can easily track the revenue that it receives from the loan of a worker to a project in another legal entity.</p></td>
</tr>
<tr class="even">
<td><p>Specify the account in which to record the true costs that are incurred from the loan of a worker to another legal entity.</p></td>
<td><p>Not available</p></td>
<td><p>The new <strong>Intercompany cost</strong> posting type is available in the <strong>Project groups</strong> form.</p></td>
<td><p>A loaning legal entity can easily track the costs that it incurs by loaning a worker to a project in another legal entity.</p></td>
</tr>
</tbody>
</table>


## More information

For more information about intercompany timesheets, see [About intercompany timesheets](about-intercompany-timesheets.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

