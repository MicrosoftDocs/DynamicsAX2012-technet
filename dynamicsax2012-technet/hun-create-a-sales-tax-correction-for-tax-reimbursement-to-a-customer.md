---
title: (HUN) Create a sales tax correction for tax reimbursement to a customer
TOCTitle: (HUN) Create a sales tax correction for tax reimbursement to a customer
ms:assetid: 9d565fe6-1463-4e41-bfe0-af0964d62181
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664338(v=AX.60)
ms:contentKeyID: 49385426
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Create a sales tax correction for tax reimbursement to a customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When a customer makes a claim for tax reimbursement, you must create a sales tax correction transaction.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Press CTRL+N to create a new journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  In the **Account** field, select the sales tax account.

5.  In the **Debit** field, enter the amount of sales tax to be reimbursed.

6.  In the **Currency** field, select the currency of the transaction.

7.  In the **Offset account** field, select the ledger account.

8.  Click the **General** tab.

9.  In the **Sales tax code** field, select the sales tax code of the invoice.

10. Click **Post** \> **Post** to post the invoice.

## See also

[(HUN) Create and print a tax reimbursement document](hun-create-and-print-a-tax-reimbursement-document.md)

[(HUN) Set up parameters for tax reimbursement documents](hun-set-up-parameters-for-tax-reimbursement-documents.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

