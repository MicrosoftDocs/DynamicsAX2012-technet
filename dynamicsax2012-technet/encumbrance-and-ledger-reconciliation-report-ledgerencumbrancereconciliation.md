---
title: Encumbrance and ledger reconciliation report (LedgerEncumbranceReconciliation)
TOCTitle: Encumbrance and ledger reconciliation report (LedgerEncumbranceReconciliation)
ms:assetid: 2a2ba138-ac5d-4911-8fe1-63820970f3f4
ms:mtpsurl: https://technet.microsoft.com/library/Hh335139(v=AX.60)
ms:contentKeyID: 36687349
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.LedgerEncumbranceReconciliation
- encumber
- budget reservation
- Encumbrance reconciliation report
---

# Encumbrance and ledger reconciliation report (LedgerEncumbranceReconciliation) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Encumbrance and ledger reconciliation** report identifies imbalances between budget reservations for encumbrances and pre-encumbrances, and the corresponding budget register entries that are tracked in the general ledger. You can create separate detail and summary versions of the report, and select encumbrances, pre-encumbrances, or both for the same report.

Detail reports display individual purchase orders, purchase requisitions, and budget register entries for the financial dimension that you select. You can create detail reports that display encumbrance and pre-encumbrance amounts that are in balance and out of balance. You can also create differences-only detail reports that display only encumbrance and pre-encumbrance amounts that are out of balance.

Summary reports display totals for encumbrances and pre-encumbrances for the financial dimension that you select. As with the detail reports, you can include in-balance and out-of-balance amounts, or create differences-only reports that display only amounts that are out of balance.

## Prerequisites

Before you run this report, make sure that the following prerequisites have been set up:

  - **Enable budget control** – Budget control is not required to create encumbrances, but it is required to create budget register entries for encumbrances. For more information, see [Set up budget control](set-up-budget-control.md).

  - **Enable encumbrance process** – The encumbrance process must be enabled before encumbrances for purchase orders can be recorded in the general ledger. For more information, see [Encumber purchase orders](encumber-purchase-orders.md).

  - **Select encumbrance accounts to include on the report** – Open the **Main account categories** form and select the **ENCUMBRANCE** main account category. Click **Link main accounts**, and then select the **Linked** check box for each main account to use for encumbrances. For more information, see [Link main accounts (form)](https://technet.microsoft.com/library/hh209475\(v=ax.60\)).
    

    > [!NOTE]
    > <P>To include pre-encumbrances on the report, select the <STRONG>PRE-ENCUMBRANCE</STRONG> main account category. Click <STRONG>Link main accounts</STRONG>, and then select the <STRONG>Linked</STRONG> check box for each main account to use for pre-encumbrances.</P>



## How to create different versions of this report

You can select different combinations of the check boxes in the **Printout** field group to create the following versions of this report.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>If you select or clear the following check boxes …</p></th>
<th><p>The following report is created …</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ul>
<li><p>Select <strong>Include details</strong>.</p></li>
<li><p>Select one or both of the <strong>Include encumbrance balances</strong> and <strong>Include pre-encumbrance balances</strong> check boxes.</p></li>
</ul></td>
<td><ul>
<li><p>A detail report that displays amounts for encumbrances and pre-encumbrances, grouped by the document number and the financial dimension that you select.</p></li>
<li><p>Encumbrance and pre-encumbrance amounts that are in balance are displayed with a currency amount of 0.00 in the <strong>Difference</strong> column.</p></li>
<li><p>Encumbrance and pre-encumbrance amounts that are out of balance are displayed with a currency amount in the <strong>Difference</strong> column.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><ul>
<li><p>Select <strong>Include details</strong> and <strong>Differences only</strong>.</p></li>
<li><p>Select one or both of the <strong>Include encumbrance balances</strong> and <strong>Include pre-encumbrance balances</strong> check boxes.</p></li>
</ul></td>
<td><ul>
<li><p>A detail report that displays encumbrances and pre-encumbrances, grouped by the document number and the financial dimension that you select.</p></li>
<li><p>Encumbrance and pre-encumbrance amounts that are out of balance are displayed with a currency amount in the <strong>Difference</strong> column.</p></li>
<li><p>The report will be blank if no amounts are out of balance.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><ul>
<li><p>Clear the <strong>Include details</strong> and <strong>Differences only</strong> check boxes.</p></li>
<li><p>Select one or both of the <strong>Include encumbrance balances</strong> and <strong>Include pre-encumbrance balances</strong> check boxes.</p></li>
</ul></td>
<td><ul>
<li><p>A summary report that displays encumbrance and pre-encumbrance totals for the financial dimension that you select.</p></li>
<li><p>Encumbrance and pre-encumbrance amounts that are in balance are displayed with a currency amount of 0.00 in the <strong>Difference</strong> column.</p></li>
<li><p>Encumbrance and pre-encumbrance amounts that are out of balance are displayed with a currency amount in the <strong>Difference</strong> column.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><ul>
<li><p>Clear the <strong>Include details</strong> check box.</p></li>
<li><p>Select <strong>Differences only</strong>.</p></li>
<li><p>Select one or both of the <strong>Include encumbrance balances</strong> and <strong>Include pre-encumbrance balances</strong> check boxes.</p></li>
</ul></td>
<td><ul>
<li><p>A summary report that displays encumbrance and pre-encumbrance totals for the financial dimension that you select.</p></li>
<li><p>Encumbrance and pre-encumbrance amounts that are out of balance are displayed with a currency amount in the <strong>Difference</strong> column.</p></li>
<li><p>The report will be blank if no amounts are out of balance.</p></li>
</ul></td>
</tr>
</tbody>
</table>


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
<td><p><strong>Fiscal year</strong></p></td>
<td><p>To run the report for a specific fiscal year, select <strong>Fiscal year</strong>, and then select the fiscal year.</p></td>
</tr>
<tr class="even">
<td><p><strong>Date range</strong></p></td>
<td><p>To run the report for a date range, select <strong>Date range</strong>, and then select a date range in the <strong>From date</strong> and <strong>To date</strong> fields.</p></td>
</tr>
<tr class="odd">
<td><p><strong>From date</strong></p></td>
<td><p>If you selected <strong>Date range</strong>, select the starting date for encumbered and pre-encumbered amounts to include on the report.</p></td>
</tr>
<tr class="even">
<td><p><strong>To date</strong></p></td>
<td><p>If you selected <strong>Date range</strong>, select the ending date for encumbered and pre-encumbered amounts to include on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Dimension</strong></p></td>
<td><p>Select a financial dimension for the report. You can select from the financial dimensions that were defined in the <strong>Financial dimensions</strong> form. For more information, see <a href="https://technet.microsoft.com/library/hh209534(v=ax.60)">Financial dimensions (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include details</strong></p></td>
<td><p>Select this check box to include detailed information for encumbered and pre-encumbered amounts. Totals are displayed by document number and the financial dimension that you select.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Differences only</strong></p></td>
<td><p>Select this check box to show differences only when the budget reservations for encumbrances and pre-encumbrances do not balance with the corresponding encumbrance and pre-encumbrance accounts in the general ledger.</p></td>
</tr>
<tr class="even">
<td><p><strong>Include encumbrance balances</strong></p></td>
<td><p>Select this check box to include encumbrances on the report.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Include pre-encumbrance balances</strong></p></td>
<td><p>Select this check box to include pre-encumbrances on the report.</p></td>
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
<td><p>LedgerEncumbranceReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\LedgerEncumbranceReconciliation</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>LedgerEncumbranceReconciliation</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>General ledger</strong> &gt; <strong>Reports</strong> &gt; <strong>Reconciliation</strong> &gt; <strong>Vendor</strong> &gt; <strong>Encumbrance</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - LedgerEncumbranceReconciliationTmp table


> [!NOTE]
> <P>To determine where the data in the temp tables comes from, view the cross-references for the LedgerEncumbranceReconciliationDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About purchase order encumbrances](about-purchase-order-encumbrances.md)

[Encumber purchase orders](encumber-purchase-orders.md)

  


