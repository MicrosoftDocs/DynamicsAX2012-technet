---
title: (CHE) Payment advice report (VendOutPaymAdvice_CHEZAG)
TOCTitle: (CHE) Payment advice report (VendOutPaymAdvice_CHEZAG)
ms:assetid: b11fb81f-a2c5-408c-80ec-7f36a3ffc29e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh404046(v=AX.60)
ms:contentKeyID: 36956706
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendOutPaymAdvice_CHEZAG
---

# (CHE) Payment advice report (VendOutPaymAdvice\_CHEZAG) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment advice** report prints payment advice for vendor payments when you post the payment journal. The vendor payments that are included in this report are made by using the **EZAG (CH)** export format. You must select **EZAG (CH)** in the **Export format** field in the **Generate payments** form. This report is typically used by accounts payable payments clerks to maintain vendor payments.


> [!NOTE]
> <P>(CHE) This report is available only to legal entities whose primary address is in Switzerland.</P>



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
<td><p>VendOutPaymAdvice_CHEZAG</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutPaymAdvice_CHEZAG</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutPaymAdviceReportCH_EZAG</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>EZAG (CH)</strong>. Enter the required details, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - CustVendOutTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendOutPaymAdviceDP_CHEZAG.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[Generate payments - vendor (class form)](https://technet.microsoft.com/en-us/library/aa586980\(v=ax.60\))

  


