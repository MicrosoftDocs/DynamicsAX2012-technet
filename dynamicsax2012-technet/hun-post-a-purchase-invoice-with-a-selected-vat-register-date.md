---
title: (HUN) Post a purchase invoice with a selected VAT register date
TOCTitle: (HUN) Post a purchase invoice with a selected VAT register date
ms:assetid: a8b6f06b-6313-42da-8c0d-110414132ac4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664345(v=AX.60)
ms:contentKeyID: 49385433
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (HUN) Post a purchase invoice with a selected VAT register date [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can select the date of the VAT register for VAT reporting when you post a purchase invoice. When you post an invoice with deferred incoming tax, the VAT amount is posted to a temporary account, and then posted to the VAT account on the selected register date.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a line.

3.  In the **Name** field, select the name of the journal.

4.  Click **Lines** to open the **Journal voucher** form.

5.  In the **Account type** field, select the type of account that the transaction will be applied to.

6.  In the **Account** field, select the vendor account.

7.  In the **Description** field, select the transaction text.

8.  In the **Debit** or **Credit** field, enter the amount.

9.  In the **Offset account type** field, select the offset account.

10. In the **Offset account** field, select the ledger account.

11. Click the **General** tab.

12. In the **Date of VAT register** field, select the VAT register date.

13. Click **Validate** \> **Validate** to validate the journal.

14. Click **Post** \> **Post** to post the journal.

## See also

[(HUN) Create and post a purchase order invoice with a specific VAT register date](hun-create-and-post-a-purchase-order-invoice-with-a-specific-vat-register-date.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

