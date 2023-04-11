---
title: ADA requirements report (HcmADARequirement)
TOCTitle: ADA requirements report (HcmADARequirement)
ms:assetid: bfe39a00-b7e4-44e8-90ac-ee28d55584fb
ms:mtpsurl: https://technet.microsoft.com/library/JJ841463(v=AX.60)
ms:contentKeyID: 50411102
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.HcmADARequirement
---

# ADA requirements report (HcmADARequirement) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Print a report about physical activities, physical requirements, visual acuity, and working conditions that a worker will be subjected to while employed in a particular job or job template.

## How to work with reports

The following topics explain how to print a report and how to filter and sort the data on a report.

  - [Print or email a report](print-or-email-a-report.md)

  - [Filter the data on a report](filter-the-data-on-a-report.md)

  - [Sort the data on a report](sort-the-data-on-a-report.md)

## Details of this report

The following table explains where to find the report in the Application Object Tree (AOT) and how to navigate to the report in the Microsoft Dynamics AX client.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Name of report in the AOT</p></td>
<td><p>HcmADARequirement</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\HcmADARequirement</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>HcmADARequirement</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Human resources</strong> &gt; <strong>Common</strong> &gt; <strong>Organization</strong> &gt; <strong>Jobs</strong>. Select a job. On the <strong>Action Pane</strong>, click <strong>ADA</strong>.</p>
<p>Click <strong>Human resources</strong> &gt; <strong>Setup</strong> &gt; <strong>Organization</strong> &gt; <strong>Job templates</strong>. Select a job template and then click <strong>ADA</strong> &gt; <strong>ADA requirements</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - HcmADARequirementTmp table


> [!NOTE]
> <P>To find out where the data in the temp tables comes from, view the cross-references for the HcmADARequirementDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(USA) Comply with the Americans with Disabilities Act](usa-comply-with-the-americans-with-disabilities-act.md)

[(USA) Enter physical requirements for job templates and jobs](usa-enter-physical-requirements-for-job-templates-and-jobs.md)

  


