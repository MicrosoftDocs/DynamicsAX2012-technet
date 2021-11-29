---
title: Customer payment retention report (PSACustomerRetention)
TOCTitle: Customer payment retention report (PSACustomerRetention)
ms:assetid: a2e62f5a-1b82-4964-9765-d875f4ad1fbf
ms:mtpsurl: https://technet.microsoft.com/library/Hh334499(v=AX.60)
ms:contentKeyID: 36676487
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- retention
- reports
- project add-in
- billing rules
- customer payment retention
- SSRS_Reports.Reports.PSACustomerRetention
- retention reports
- customer retention reports
- payment retention reports
---

# Customer payment retention report (PSACustomerRetention) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Customer payment retention** report to view a summary of all customer payment retention amounts for a customer, project contract, project, or billing rule, or for any combination of these criteria.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

In the **Customer payment retention summary** field, select how you want to organize the report information. You can create a report by customer, contract, project, or billing rule. The combination of filters that you select determines what is displayed on the report. For example, if you select **Contract**, the customer payment retention totals by project contract are displayed on the report. If there are no customer payment retention amounts that meet the criteria that you select, the report is empty.

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
<td><p><strong>Customer payment retention summary</strong></p></td>
<td><p>Select how you want the report to be organized.</p></td>
</tr>
<tr class="even">
<td><p><strong>Customer account</strong></p></td>
<td><p>Select the customer whose retention amounts you want to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Contract</strong></p></td>
<td><p>Select the project contract ID for which to view customer retention amounts.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project</strong></p></td>
<td><p>Select the project ID for which to view customer retention amounts.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Billing rule</strong></p></td>
<td><p>Select the billing rule for which to view customer retention amounts.</p></td>
</tr>
</tbody>
</table>


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
<td><p>PSACustomerRetention</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PSACustomerRetention</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Customer payment retention</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Retention</strong> &gt; <strong>Customer payment retention</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PSACustomerRetentionDP.processReport

  - PSACustomerRetentionTmp table
    

    > [!NOTE]
    > <P>To determine where the data in the temp table comes from, view the cross-references for the RFQSendDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


