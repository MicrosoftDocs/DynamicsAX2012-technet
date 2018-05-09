---
title: Synchronize data by using batch jobs (Retail essentials)
TOCTitle: Synchronize data by using batch jobs (Retail essentials)
ms:assetid: 786752f6-9942-4732-a070-9f9c6b593c05
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn756402(v=AX.60)
ms:contentKeyID: 62524901
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.Dialog
- MsDynAx060.Forms.RetailCDXDownloadSessionDataStore
---

# Synchronize data by using batch jobs (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes the various batch jobs that you must run in Retail essentials. Run these batch jobs to synchronize data between headquarters and the retail store, synchronize setup tasks with their relevant components, or update components, such as product assortments or delivery modes, when changes are made.

The following table describes the different batch jobs that you can run in Retail essentials. You can set up these jobs to run on a regular basis, as a batch process, or you can manually run the jobs when you make changes. For information about configuring jobs and subjobs, see [Configure jobs and subjobs in Retail Scheduler (Retail essentials)](configure-jobs-and-subjobs-in-retail-scheduler-retail-essentials.md).

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Batch job</p></th>
<th><p>Description</p></th>
<th><p>Path</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Process delivery modes</p></td>
<td><p>Run this job to link retail stores and retail products with available delivery modes.</p>
<p>For more information about how to set up delivery modes, see <a href="set-up-modes-of-delivery.md">Set up modes of delivery</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Data synchronization</strong> &gt; <strong>Data processing</strong> &gt; <strong>Process delivery modes</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Transfer to pay</p></td>
<td><p>Run this job to export payroll transactions to an external file.</p>
<p>For more information about how to run this process, see <a href="https://technet.microsoft.com/en-us/library/aa596780(v=ax.60)">Transfer to pay (class form)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Employees</strong> &gt; <strong>Time and attendance</strong> &gt; <strong>Transfer to pay</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Generate account activity</p></td>
<td><p>Run this job to summarize the accounting totals to export to a third-party accounting system.</p>
<p>For more information about how to export account activity, see <a href="export-accounting-information-retail-essentials.md">Export accounting information (Retail essentials)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Financials</strong> &gt; <strong>Accounting export</strong> &gt; <strong>Generate account activity</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Export account activity</p></td>
<td><p>Run this job to export totals from the accounting export profile to a directory that is accessible to a third-party accounting system</p>
<p>For more information about how to export account activity, see <a href="export-accounting-information-retail-essentials.md">Export accounting information (Retail essentials)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Financials</strong> &gt; <strong>Accounting export</strong> &gt; <strong>Export account activity</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Process assortments</p></td>
<td><p>Run this job to send product assortments to retail stores. This job is automatically run when an assortment is published. You should also set up the assortments scheduler to run periodically as a batch job.</p>
<p>For more information about how to process product assortments, see <a href="configure-the-scheduler-job-for-assortments-retail-essentials.md">Configure the scheduler job for assortments (Retail essentials)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Data synchronization</strong> &gt; <strong>Process assortments</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Send email receipts</p></td>
<td><p>Run this job to generate and send email receipts to customers who requested them.</p>
<p>For more information about how to set up email receipts, see <a href="set-up-receipt-options-retail-essentials.md">Set up receipt options (Retail essentials)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Data synchronization</strong> &gt; <strong>Send email receipts</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Clean up staging</p></td>
<td><p>Run this job as part of the migration process when you are migrating data from Microsoft Dynamics Retail Management System (RMS) to Retail essentials.</p>
<p>You only need to run this process if field mappings are changed or if something is not working correctly.</p>
<p>For more information about how to clean up staging data, see <a href="migrate-data-from-microsoft-dynamics-retail-management-system-retail-essentials.md">Migrate data from Microsoft Dynamics Retail Management System (Retail essentials)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Data synchronization</strong> &gt; <strong>Setup</strong> &gt; <strong>Data import export framework</strong> &gt; <strong>Staging cleanup</strong>.</p></td>
</tr>
<tr class="even">
<td><p>Post inventory</p></td>
<td><p>Run this job to post inventory journals that were created as part of the retail statement posting process.</p>
<p>For more information about how to post retail statements, see <a href="create-and-post-a-statement-retail-essentials.md">Create and post a statement (Retail essentials)</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Financials</strong> &gt; <strong>POS posting</strong> &gt; <strong>Post inventory</strong>.</p></td>
</tr>
<tr class="odd">
<td><p>Process status messages</p></td>
<td><p>Run this job to update the download session list with the latest status.</p>
<p>For more information about data distribution jobs, see <a href="view-or-cancel-retail-data-distribution-sessions.md">View or cancel retail data distribution sessions</a>.</p></td>
<td><p>Click <strong>Retail essentials</strong> &gt; <strong>Data synchronization</strong> &gt; <strong>Download sessions</strong>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

