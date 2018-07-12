---
title: (NOR) Set up the OCR method of payment
TOCTitle: (NOR) Set up the OCR method of payment
ms:assetid: 5b0df91c-c259-4c43-9dcd-e8520e9f207e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242489(v=AX.60)
ms:contentKeyID: 36057356
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Set up the OCR method of payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By using optical character recognition (OCR) payments, you can receive payments electronically from customers. Before you can accept payments, you can attach the OCR method of payment to a customer record to make it the default method of payment for invoicing. You can also change the method of payment for the record before you settle an invoice. Refer to the following table for information about the methods of payment and the file formats that you can use for customers and vendors.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method of payment</p></th>
<th><p>Export file format</p></th>
<th><p>Import file format</p></th>
<th><p>Return file format</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>OCR</p></td>
<td><p></p></td>
<td><p>OCR+AG innlesning (NO)</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>AVG</p></td>
<td><p>Avtalegiro (NO)</p></td>
<td><p>OCR+AG innlesning (NO)</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>BBS</p></td>
<td><p>BBS, eFaktura, AG, DirRem (NO)</p></td>
<td><p>BBS, eFaktura, AG, OCR, DirRem (NO)</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>DIR</p></td>
<td><p>BBS Direkte Remittering (NO)</p></td>
<td><p></p></td>
<td><p>BBS Direkte Remittering (NO)</p></td>
</tr>
<tr class="odd">
<td><p>TP1</p></td>
<td><p>TelePay 2.01 (NO)</p></td>
<td><p></p></td>
<td><p>TelePay 2.01 (NO)</p></td>
</tr>
</tbody>
</table>


The method of payment that is attached to the customer is not the current method of payment in the following two scenarios:

  - When you import the files that the bank sends, you must create and use the method of payment for OCR imports. You do not have to attach the method of payment to the customer record.

  - When the OCR file is read, the method of payment may be changed to direct debit or eInvoice for the customer.

<!-- end list -->

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a new method of payment. For more information, see [Set up a file format for a method of payment for customers](set-up-a-file-format-for-a-method-of-payment-for-customers.md).

3.  In the **Method of payment** field, enter OCR as the method of payment to receive payments electronically from customers.
    

    > [!NOTE]
    > <P>Other methods of payment include <STRONG>TelePay (NO)</STRONG>, <STRONG>TelePay 2.0 (NO)</STRONG>, and <STRONG>BBS Direkte Remittering (NO)</STRONG>, which can be used for both customer and vendor payments. In addition, the <STRONG>TelePay 1.06 (NO)</STRONG> method of payment is used only for vendor payments.</P>



4.  Click the **File formats** FastTab, and then in the **Import format** field, select **OCR+AG innlesning (NO)** as the import file format for the OCR method of payment.

5.  Click the **Payment control** tab, and then select additional validation criteria that are used when you post the journal by using the OCR method of payment.

6.  Close the form.

## See also

[(NOR) OCR payments](nor-ocr-payments.md)

  


