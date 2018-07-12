---
title: (CAN, USA) Accrued purchases report (VendAccruedPurchases_NA)
TOCTitle: (CAN, USA) Accrued purchases report (VendAccruedPurchases_NA)
ms:assetid: 8a9e1dc0-cf71-4f5f-86d3-f0db27725806
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa598272(v=AX.60)
ms:contentKeyID: 37832019
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendAccruedPurchases_NA
---

# (CAN, USA) Accrued purchases report (VendAccruedPurchases\_NA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Accrued purchases** report displays details about product receipts that have been entered and posted, but not invoiced, as of the cutoff date that you specify. The report contains data that you can use to reconcile one or more accrued purchases accounts. Invoice details are displayed on the report when one of the following conditions is true:

  - The receipt transaction date is before or equal to the cutoff date, and the invoice transaction date is after the cutoff date.

  - The invoice transaction date is before or equal to the cutoff date, and the receipt transaction date is after the cutoff date.


> [!NOTE]
> <P>(CAN, USA) This report is available only to legal entities whose primary address is in Canada or the United States.</P>



## How to filter the data on this report

When you generate this report, the following default parameters are displayed. You can use these parameters to filter the data that will be displayed on the report. For more information, see [Filter the data on a report](filter-the-data-on-a-report.md).

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
<td><p><strong>Cutoff date</strong></p></td>
<td><p>Enter a cutoff date. The report will include information about product receipts that were entered, but not invoiced, as of this date. The default date is the system date.</p></td>
</tr>
<tr class="even">
<td><p><strong>Purchase order receipts with GL postings</strong></p></td>
<td><p>Select this check box if the report should list only receipts that have not been completely invoiced, but that have transactions that were posted to the general ledger. By default, the check box is selected.</p></td>
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
<td><p>VendAccruedPurchases_NA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\ VendAccruedPurchases_NA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendAccruedPurchases_NA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Procurement and sourcing</strong> &gt; <strong>Reports</strong> &gt; <strong>Status</strong> &gt; <strong>Accrued purchases</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendAccruedPurchasesTmp table


> [!NOTE]
> <P>To determine where the data in the temp table comes from, view the cross-references for the VendAccruedPurchases_NADP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


