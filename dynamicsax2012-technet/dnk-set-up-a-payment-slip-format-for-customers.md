---
title: (DNK) Set up a payment slip format for customers
TOCTitle: (DNK) Set up a payment slip format for customers
ms:assetid: a1223925-466c-4ef7-891c-6be505e1472e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209451(v=AX.60)
ms:contentKeyID: 36058776
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- format
- Denmark
- payment slip
---

# (DNK) Set up a payment slip format for customers [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Businesses commonly attach printed payment slips to invoices to assist customers and provide a payment reference for posting and settlement. The payment slip can be used for project or service invoices, collection letters, interest notes, and account statements, in addition to sales invoices and free text invoices. To process payment slips, first set up your creditor identification number and payment slip attachment formats.

## Set up a creditor ID number

Enter your company creditor identification number as provided by your financial institution. This number is used as a reference when customer payments are received through financial institutions.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Bank account information** FastTab, and in the **FI-Creditor ID** field, enter your unique eight-digit creditor ID.

3.  Close the form to save your changes.

## Set up a payment slip format for invoices, notes, letters, and statements

Set up a format for a payment slip attachment to accompany sales invoices, free text invoices, interest notes, collection letters, and account statements.

1.  Click **Accounts receivable** \> **Setup** \> **Forms** \> **Form setup**.

2.  Click the **Invoice** tab, and in the **Associated payment attachment on customer invoice** field, select the payment slip attachment format. Choose from the following options:
    
      - **None** – Do not print a payment slip. Choose this option if the payment amount is in a currency other than Danish kroner (DKK).
    
      - **FIK 751** – Print an FIK 751 payment slip if you intend to write the payment amount and due date on the payment slip manually.
    
      - **FIK 752** – Print an FIK 752 payment slip if you intend to use a computer-generated payment slip with a preprinted payment amount and due date.

3.  Click the **Free text invoice**, **Interest note**, **Collection letter**, and **Account statement** tabs to select a payment slip attachment format for each document type.

4.  Close the form to save your changes.

## Set up a payment slip format for project invoices

Set up a format for a payment slip attachment to accompany project invoices.

1.  Click **Project management and accounting** \> **Setup** \> **Forms** \> **Form setup**.

2.  Click the **Invoice** tab, and in the **Associated payment attachment on the project invoice** field, select the payment slip to print with the invoice. Choose from the following options:
    
      - **None** – Do not print a payment slip. Choose this option if the payment amount is in a currency other than Danish kroner (DKK).
    
      - **FIK 751** – Print an FIK 751 payment slip if you intend to write the payment amount and due date on the payment slip manually.
    
      - **FIK 752** – Print an FIK 752 payment slip if you intend to use a computer-generated payment slip with a preprinted payment amount and due date.

3.  Close the form to save your changes.

## Assign a payment slip format to a customer account

After you set up the payment slip attachment format for sales invoices, free text invoices, interest notes, collection letters, project invoices, and account statements, you can assign specific formats for a selected customer.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Create a new customer or select an existing customer.

3.  Click the **Invoice and delivery** FastTab, and in the **On a customer invoice**, **On a free text invoice**, **On an interest note**, **On a collection letter**, **On a project invoice**, and **On an account statement** fields, select the payment slip format to accompany each document type for the selected customer.

4.  Close the form to save your changes.

## See also

[(DNK) Post a sales invoice with a payment slip](dnk-post-a-sales-invoice-with-a-payment-slip.md)

[(DNK) Post a free text invoice with a payment slip](dnk-post-a-free-text-invoice-with-a-payment-slip.md)

[(DNK) Post a project invoice with a payment slip](dnk-post-a-project-invoice-with-a-payment-slip.md)

[Legal entities (form)](https://technet.microsoft.com/en-us/library/hh242860\(v=ax.60\))

[Form setup (form)](https://technet.microsoft.com/en-us/library/aa589956\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

