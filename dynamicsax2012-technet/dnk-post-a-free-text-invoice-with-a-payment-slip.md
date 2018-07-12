---
title: (DNK) Post a free text invoice with a payment slip
TOCTitle: (DNK) Post a free text invoice with a payment slip
ms:assetid: 8268d812-02ae-48e3-a31d-25ad57095f40
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209313(v=AX.60)
ms:contentKeyID: 36058370
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Denmark
- payment slip
- free text invoice
audience: Application User
ms.search.region: Denmark
---

# (DNK) Post a free text invoice with a payment slip 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can post a free text invoice with a payment slip attachment in a specified format. The payment slip is printed with the creditor identification number and invoice number to identify the payment.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Create a new free text invoice or select an existing free text invoice.

3.  Click the **Payment** tab, and in the **Associated payment attachment on free text invoice** field, select the payment slip to print for a free text invoice. Choose from the following options:
    
      - **None** – Do not print a payment slip. Choose this option if the payment amount is in a currency other than Danish kroner (DKK).
    
      - **FIK 751** – Print an FIK 751 payment slip if you intend to write the payment amount and due date on the payment slip manually.
    
      - **FIK 752** – Print an FIK 752 payment slip if you intend to use a computer-generated payment slip with a preprinted payment amount and due date.

4.  Click **Post** to open the **Post free text invoice** form.

5.  Select the **Posting** and **Print invoice** check boxes to post the free text invoice with the payment slip attachment.

6.  Close the form to save your changes.

## See also

[(DNK) Set up a payment slip format for customers](dnk-set-up-a-payment-slip-format-for-customers.md)

[Free text invoice (form)](https://technet.microsoft.com/en-us/library/aa556897\(v=ax.60\))

  


