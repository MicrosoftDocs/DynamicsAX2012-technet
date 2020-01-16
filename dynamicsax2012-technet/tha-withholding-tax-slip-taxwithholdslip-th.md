---
title: (THA) Withholding tax slip (TaxWithholdSlip_TH)
TOCTitle: (THA) Withholding tax slip (TaxWithholdSlip_TH)
ms:assetid: 17725562-3b08-413a-9a1d-fe3a3a65e99e
ms:mtpsurl: https://technet.microsoft.com/library/Hh335134(v=AX.60)
ms:contentKeyID: 36687344
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.TaxWithholdSlip_TH
- (THA)
- Withholding tax slip
---

# (THA) Withholding tax slip (TaxWithholdSlip\_TH) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Withholding tax slip** report prints the details of withholding tax slips for legal entities operating in Thailand. This report is printed in the withholding tax currency and is sorted by the vendor account and the journal number. This report is typically used by accounting managers, accounts payable coordinators, and accountants to maintain vendor payment details.


> [!NOTE]
> <P>(THA) This report is available only to legal entities whose primary address is in Thailand.</P>



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
<td><p>TaxWithholdSlip_TH</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\TaxWithholdSlip_TH</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>TaxWithholdSlip_TH</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Print</strong> &gt; <strong>Withholding tax slip</strong>.</p>
<p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Print</strong> &gt; <strong>Withholding tax slip</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - TaxWithholdSlipTmp\_TH table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the TaxWithholdSlipDP_TH.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


