---
title: (SWE) Payment slip report (Giro)
TOCTitle: (SWE) Payment slip report (Giro)
ms:assetid: faf80324-1c14-4df5-aeef-ef25595ec428
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433527(v=AX.60)
ms:contentKeyID: 36941313
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- SSRS_Reports.Reports.Giro
---

# (SWE) Payment slip report (Giro) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Payment slip** report is displayed when you use a Giro payment format to generate a payment for a customer invoice or vendor invoice. The details that are displayed in this report depend on the payment format that is used to generate a payment. You can generate a Giro payment by using the following payment formats:

  - **Bankgirot Autogiro (SE)** – The report displays the details of vendor transactions together with the **Sequence number**, **Routing number**, and total amounts of the transactions.

  - **Bankgirot OCR (SE)** – The report displays the details of import payments.

  - **Postgirot OCR (SE)** – The report displays the details of Postgirot payments for debit invoices.

  - **Bankgirot Max (SE)** – The report displays details of Bankgirot Max payment files that are imported to customer payment journals.

This report is typically used by collections agents, collections managers, accountants, accounts receivable managers, and financial controllers to inquire into the status of collections and customer invoices and to maintain collections transactions.


> [!NOTE]
> <P>(SWE) This report is available only to legal entities whose primary address is in Sweden.</P>



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
<td><p>Giro</p></td>
</tr>
<tr class="even">
<td><p>Location of report in the AOT</p></td>
<td><p>SSRS Reports\Reports\Giro</p></td>
</tr>
<tr class="odd">
<td><p>Menu item of the report</p></td>
<td><p>GiroReport</p></td>
</tr>
<tr class="even">
<td><p>Navigation to the report</p></td>
<td><p>Click <strong>Accounts payable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Generate payments</strong>. In the <strong>Generate payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment that uses the <strong>Bankgirot Autogiro (SE)</strong> or <strong>Postgirot (SE)</strong> payment format, and then click <strong>Dialog</strong>. Enter the required details, and then click <strong>OK</strong>.</p>
<p>–or–</p>
<p>Click <strong>Accounts receivable</strong> &gt; <strong>Journals</strong> &gt; <strong>Payments</strong> &gt; <strong>Payment journal</strong>. Click <strong>Lines</strong>. In the <strong>Journal voucher</strong> form, click <strong>Functions</strong> &gt; <strong>Import payments</strong>. In the <strong>Load diskette with payments</strong> form, in the <strong>Method of payment</strong> field, select the method of payment that uses the <strong>Bankgirot OCR (SE)</strong> or <strong>Bankgiro Max (SE)</strong> import format, and then click <strong>OK</strong>. Enter the required details, and then click <strong>OK</strong>.</p></td>
</tr>
</tbody>
</table>


## Where the data in this report comes from

The data on this report comes from the following sources:

  - GiroReportTmp table
    

    > [!NOTE]
    > <P>To find out where the data in the temp table comes from, view the cross-references for the GiroReportDP.processReport class.</P>



If you are a developer, you can learn more about where the data on a report comes from by using the following procedure.

1.  Open the AOT.

2.  Locate the report in the **SSRS Reports**\\**Reports** node.

3.  Right-click the report and click **Add-Ins** \> **Cross-reference** \> **Using (instant view)**.

## See also

[(SWE) Import BG direct debit payment returns to a general journal](swe-import-bg-direct-debit-payment-returns-to-a-general-journal.md)

[(SWE) Import BG Max payments to a payment journal](swe-import-bg-max-payments-to-a-payment-journal.md)

[(SWE) Postgirot (SE) report (VendOutPaymControl\_SE)](swe-postgirot-se-report-vendoutpaymcontrol-se.md)

[(SWE) Bankgirot OCR (SE) report (CustInPaymSE)](swe-bankgirot-ocr-se-report-custinpaymse.md)

  


