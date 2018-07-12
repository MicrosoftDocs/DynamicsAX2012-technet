---
title: (CAN, USA) Vendor payment journal report (VendPaymentJournal_NA)
TOCTitle: (CAN, USA) Vendor payment journal report (VendPaymentJournal_NA)
ms:assetid: dfe8e809-77c1-4d07-a51e-eafa2d39ed32
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh524744(v=AX.60)
ms:contentKeyID: 37072040
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.VendPaymentJournal_NA
---

# (CAN, USA) Vendor payment journal report (VendPaymentJournal\_NA) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Vendor payment journal** report displays the payment details and settlement details for a vendor payment journal that you can select in the **Payment journal** form. This report is used to view the account and payment details for individual vendors. This report is typically used by accounts payable payments clerks, chief financial officers, accountants, accounting managers, accounting supervisors, and financial controllers.


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
<td><p><strong>Journal batch number</strong></p></td>
<td><p>The batch number of the ledger journal that the vendor payments are posted to.</p></td>
</tr>
<tr class="even">
<td><p><strong>Account type</strong></p></td>
<td><p>The type of account that the payment transaction is applied to. The default value for this field is <strong>Vendor</strong>. This field can also display the account type as <strong>Ledger</strong>, <strong>Customer</strong>, <strong>Project</strong>, <strong>Fixed assets</strong>, or <strong>Bank</strong>.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Check number</strong></p></td>
<td><p>The number of the check that is used for payment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Canceled</strong></p></td>
<td><p>Indicates whether the vouchers that are transferred from the payment journal are canceled.</p></td>
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
<td><p>VendPaymentJournal_NA</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\VendPaymentJournal_NA</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>VendPaymentJournal_NA</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Select a journal name, and then click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Print</strong> &gt; <strong>Vendor payment journal</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - VendPaymentJournalTmp\_NA table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the VendPaymentJournalDP_NA.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

  


