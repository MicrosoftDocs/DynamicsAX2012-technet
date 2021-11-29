---
title: (ITA) Payment control report (CustOutPaymControl_IT)
TOCTitle: (ITA) Payment control report (CustOutPaymControl_IT)
ms:assetid: 73442d4c-2f2d-4623-b64f-e9f508788d77
ms:mtpsurl: https://technet.microsoft.com/library/Hh433502(v=AX.60)
ms:contentKeyID: 36941271
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Print
- report
- SSRS_Reports.Reports.CustOutPaymControl_IT
- (ITA)
---

# (ITA) Payment control report (CustOutPaymControl\_IT) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment control** report prints the payment control details for customer payments. This report is typically used by accounts receivable payments clerks to maintain customer payments.


> [!NOTE]
> <P>(ITA) This report is available only to legal entities whose primary address is in Italy.</P>



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
<td><p>CustOutPaymControl_IT</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\CustOutPaymControl_IT</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>CustOutPaymControl_IT</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Bill of exchange</strong> &gt; <strong>Draw bill of exchange journal</strong>. Select a journal name, and then click <strong>Lines</strong>. Click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Method of payment</strong> field, select the method of payment that uses the <strong>Bill of exchange document</strong> export format and the <strong>Italy</strong> remittance format. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>. In the <strong>Bill of exchange document</strong> form, enter the details required to print the report, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table

  - TmpAccountSum table
    

    > [!NOTE]
    > <P>To find out where the data in the temp tables comes from, view the cross-references for the CustOutPaymControlDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Bill of exchange document (class form)](https://technet.microsoft.com/library/aa587352\(v=ax.60\))

  


