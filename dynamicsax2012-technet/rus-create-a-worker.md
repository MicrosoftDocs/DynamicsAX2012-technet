---
title: (RUS) Create a worker
TOCTitle: (RUS) Create a worker
ms:assetid: d9222dce-5d8c-41d4-81b4-87e964fde960
ms:mtpsurl: https://technet.microsoft.com/library/Dn452012(v=AX.60)
ms:contentKeyID: 56713184
author: tonyafehr
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- worker
- Forms.DirPartyTable
- Forms.GlobalAddressBookListPage
- tax registration
- Forms.LogisticsPostalAddress
- Forms.HcmWorkerNewWorker
- Forms.RHRMWorkerListPage
- Forms.RHRMWorkerNewWorker
- core worker
- social insurance fund
- d9222dce-5d8c-41d4-81b4-87e964fde960
- MsDynAx060.Forms.DirPartyTable
- MsDynAx060.Forms.LogisticsPostalAddress
- MsDynAx060.Forms.HcmWorkerNewWorker
- MsDynAx060.Forms.GlobalAddressBookListPage
- MsDynAx060.Forms.RHRMWorkerListPage
- MsDynAx060.Forms.RHRMWorkerNewWorker
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a worker 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to create a worker, make that worker a core worker, and hire the core worker as an employee.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Configuration task</p></td>
<td><ul>
<li><p>Create a legal entity. For more information, see &quot;Create tax registration numbers and insurance fund information for a legal entity&quot; in <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Create employee categories, job titles, positions, and branches. For more information, see <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a> and <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>. </p></li>
<li><p>Set up the organizational information and reserve a position for a department. For more information, see &quot;Create a department and assign it to a branch&quot; and &quot;Reserve a position for a department&quot; in <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create a worker record

To create a worker, follow these steps:

1.  Click **Home** \> **Common** \> **Global address book**.

2.  On the **New** tab, click **Party** to create a new party.

3.  In the **Record type** field, select **Person** to indicate that the party is a person.

4.  In the **First name** field, enter the first name of the worker, and then select the required legal entity in the **Address books** field. The added person belongs to the **Global address book** that is available to other legal entities for future reference.

5.  In the **Global address book** list page, select the employee record, and then click **Worker** to define this worker as a core worker for the company.
    

    > [!NOTE]
    > <P>The <STRONG>Legal entity</STRONG> and <STRONG>Personnel number</STRONG> are displayed for the selected worker.</P>



6.  In the **Worker type** field, select **Employee** as the worker type.

7.  Click **Hire new worker** to complete the process of making the person a core worker.

## Assign the worker to be used in Payroll (Russia)

Now that you have created the worker record in the **Global address book**, you must assign the worker record to be used in Payroll (Russia) as an employee or a contractual worker.

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. On the **New** tab, click **Create new worker** to create a core worker as a new employee or a contractual worker.

2.  In the **Worker** field, select the core worker, and then click **Create** to make the worker an employee or a contractual worker.

3.  In the **Employees** form, select the employee record, and then click **Taxes**.

4.  In the **Manage addresses** form, click **Add**.

Use the information in the following table to add the tax registration identification number and the social insurance fund number for Russia.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Name or description</strong></p></td>
<td><p>The name or short description of the address record. The text in this field is used as the default delivery name on business documents such as sales orders.</p></td>
</tr>
<tr class="even">
<td><p><strong>Purpose</strong></p></td>
<td><p>Select the purpose of the address in this instance. For example, select <strong>Delivery</strong> if this address is used for deliveries. You can select more than one purpose.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Country/region</strong></p></td>
<td><p>On the <strong>Address</strong> FastTab, select <strong>RUS</strong> as the <strong>Country/region</strong> code for Russia.</p></td>
</tr>
<tr class="even">
<td><p><strong>Registration type</strong></p></td>
<td><p>On the <strong>Tax registration</strong> FastTab, click <strong>Add</strong>, and then select one of the following tax registration types:</p>
<ul>
<li><p>INN – The unique code for the individual taxpayer.</p></li>
<li><p>SNILS – The unique code for the physical person who is insured in the federal social insurance and pension funds.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Registration number</strong></p></td>
<td><p>On the <strong>Tax registration</strong> FastTab, click <strong>Add</strong>, and then enter a valid tax registration number for the registration type.</p></td>
</tr>
</tbody>
</table>


Any change in the employee status is sent as a notification to the Accounts payable clerk if the employee is an advance holder.

## Next step

[(RUS) Hire, transfer, and dismiss a worker](rus-hire-transfer-and-dismiss-a-worker.md)

## Related tasks

[(RUS) Configure staff administration information for workers](rus-configure-staff-administration-information-for-workers.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.


<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>CIS Payroll</strong> and <strong>CIS Staff administration</strong> configuration keys.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p><strong>Human Resource administrator</strong></p></li>
<li><p><strong>Recruiter</strong></p></li>
<li><p><strong>Payroll administrator</strong></p></li>
</ul>
<p>To configure the creation of a worker, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable project accounting process</strong> (ProjProjectAccountingProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitInquire)</p></li>
<li><p><strong>Inquire into payroll position and worker setup</strong> (PayrollPositionWorkerSetupInquire)</p></li>
<li><p><strong>Inquire into workers</strong> (HcmWorkerInquire)</p></li>
<li><p><strong>Maintain audit policies</strong> (ComplianceMgmtAuditPoliciesMaintain)</p></li>
<li><p><strong>Maintain project master</strong> (ProjProjectMasterMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To configure the creation of a worker, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privileges</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Create workers</strong></p></td>
<td><p>HcmWorkerCreate</p></td>
<td><p>Create a worker.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


