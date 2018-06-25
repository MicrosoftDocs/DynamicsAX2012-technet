---
title: (FRA) FRAFB report (VendOutPaymAdvice_FRAFB)
TOCTitle: (FRA) FRAFB report (VendOutPaymAdvice_FRAFB)
ms:assetid: 17f8bed9-738f-4a8c-9f4a-462bb8b23aac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh335135(v=AX.60)
ms:contentKeyID: 36687345
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendOutPaymAdvice_FRAFB
- Payment advice
- Vendors
---

# (FRA) FRAFB report (VendOutPaymAdvice\_FRAFB) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **FRAFB** report prints the payment advice for the electronic vendor payment. This report is printed when you post the payment journal and can be sent together with the payment check to the vendor. This report is typically used by credit managers and collections managers.

Before you print this report, you must set up a payment method with **cfonb - virements (fr)** as the export format in the **Methods of payment - vendors** form.


> [!NOTE]
> <P>(FRA) This report is available only to legal entities whose primary address is in France.</P>



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
<td><p><strong>File name</strong></p></td>
<td><p>Enter the file path and file name of the payment details file.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment date</strong></p></td>
<td><p>Enter the date when payment is made to the vendor.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Control report</strong></p></td>
<td><p>Select this check box to print the control report.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment advice</strong></p></td>
<td><p>Select this check box to print the payment advice.</p></td>
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
<td><p>VendOutPaymAdvice_FRAFB</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendOutPaymAdvice_FRAFB</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendOutPaymAdvice_FRAFB</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. Click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Export format</strong> field, select <strong>cfonb - virements (fr)</strong>. In the <strong>Bank account</strong> field, select a bank account, and then click <strong>Dialog</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendOutPaymAdviceTmp\_FRAFB table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendOutPaymAdviceDP_FRAFB.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

