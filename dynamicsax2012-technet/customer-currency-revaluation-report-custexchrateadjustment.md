---
title: Customer currency revaluation report (CustExchRateAdjustment)
TOCTitle: Customer currency revaluation report (CustExchRateAdjustment)
ms:assetid: 87b853b4-3ea1-4fe9-a324-2422d3aa7d77
ms:mtpsurl: https://technet.microsoft.com/library/Aa598032(v=AX.60)
ms:contentKeyID: 36956700
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.CustExchRateAdjustment
---

# Customer currency revaluation report (CustExchRateAdjustment) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this report to view and print the details of the foreign currency revaluation that you are posting. The report shows:

  - The balances, in the original currency and the accounting currency, that correspond to the before and after revaluations for customers who have revalued transactions.

  - The revaluation amounts, by customer.

  - The sums of the revaluation transactions, by currency.


> [!IMPORTANT]
> <P>You can view and print this report only if you select the <STRONG>Print</STRONG> check box in the <STRONG>Foreign currency revaluation</STRONG> form immediately before you run the revaluation. The report is not saved in Microsoft Dynamics AX for later reference. You can always view the ledger and customer transactions that are created in a particular run of the revaluation. For more information, see <A href="https://technet.microsoft.com/library/aa586009(v=ax.60)">Customer foreign currency revaluation (form)</A>.</P>



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
<td><p>CustExchRateAdjustment</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>\SSRS Reports\Reports\CustExchRateAdjustment</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustExchRateAdjustment</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Periodic</strong> &gt; <strong>Foreign currency revaluation</strong>. Click <strong>Foreign currency revaluation</strong>, select the <strong>Print</strong> check box, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - DimensionAttributeValueCombination table

  - CustExchRateAdjustmentTmp table

If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[About foreign currency revaluations for open customer transactions](about-foreign-currency-revaluations-for-open-customer-transactions.md)

  


