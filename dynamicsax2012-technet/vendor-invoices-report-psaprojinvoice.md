---
title: Vendor invoices report (PSAProjInvoice)
TOCTitle: Vendor invoices report (PSAProjInvoice)
ms:assetid: 68916f4e-7045-466c-9b9c-76eb6308955b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh334489(v=AX.60)
ms:contentKeyID: 36676476
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reports
- project add-in
- SSRS_Reports.Reports.PSAProjInvoice
- retention details
- vendor payment retention
- project contract details
- retention amount details
- vendor invoices reports
- vendor payment reports
---

# Vendor invoices report (PSAProjInvoice) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Vendor invoices** report to view a summary of all vendor invoices for a vendor, project, or project contract that have a pay-when-paid setting.

## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

In the **Customer payment retention summary** field, select whether you want to organize the report information by vendor or by project. The combination of filters that you select determines what is displayed on the report. For example, if you select **Vendor**, vendor invoice totals by vendor are displayed. If there are no vendor payment retention amounts that meet the selection criteria that you select, the report is empty.

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
<td><p><strong>From date</strong></p></td>
<td><p>Enter the starting date of the date range for which to view vendor invoices.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>Enter the ending date of the date range.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Customer payment retention summary</strong></p></td>
<td><p>Select whether you want to organize the report by vendor or by project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor</strong></p></td>
<td><p>Select a vendor to view retention amounts for a specific vendor.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Project</strong></p></td>
<td><p>Select a project to view retention amounts for a specific project.</p></td>
</tr>
<tr class="even">
<td><p><strong>Project contract</strong></p></td>
<td><p>Select a project contract to view retention amounts for a specific contract.</p></td>
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
<td><p>PSAProjInvoice</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\PSAProjInvoice</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>Vendor invoices</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Project management and accounting</strong> &gt; <strong>Reports</strong> &gt; <strong>Retention</strong> &gt; <strong>Vendor invoices with pay when paid</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - PSAProjInvoiceDP.processReport

  - PSAProjInvoiceHeaderTmp table

  - PSAProjInvoiceTmp table
    

    > [!NOTE]
    > <P>To determine where the data in the temp tables comes from, view the cross-references for the RFQSendDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Vendor invoices with pay when paid (form)](https://technet.microsoft.com/en-us/library/hh227358\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

