---
title: (SWE) Import and post a payment return file for a partially used credit memo
TOCTitle: (SWE) Import and post a payment return file for a partially used credit memo
ms:assetid: 8589284e-6bbd-4f2a-aed9-927994372bcb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209326(v=AX.60)
ms:contentKeyID: 36058406
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Sweden
- Bankgirot
- credit memo
- payment return
---

# (SWE) Import and post a payment return file for a partially used credit memo [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can settle partially-used credit memos that have a remaining balance that is greater than the total of a vendor's debit invoices. When you import a payment return file from BankGiroCentralen (BGC), the partial credit memo is verified if the amount matches the associated journal voucher number and journal number. If the partial credit memo amount does not match, the payment line is adjusted to reflect the difference, and a new payment line showing the credit is created and marked as **Approved**. The status of the payment line with the debit invoice amount is updated to **Approved**.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment transfer**.

2.  Click **Return file - vendor** to open the **Load diskette with payments** form.

3.  In the **Method of payment** field, select the method of payment.

4.  Click **OK** to open the **Bankgirot (SE)** form.

5.  In the **File name** field, enter file name and path for the payment return file. The file is matched against the payment line.

6.  Click **OK** to close the form.

7.  In the **Payment transfer** form, select the new payment journal line with the credit amount, and then click **Post** to open the **Post payments** form.

8.  In the **New journal name** field, enter a journal name.

9.  Click **OK** to post the journal.

10. Close the form to save your changes.

## See also

[(SWE) Generate and transfer a Bankgiro payment file for a partially used credit memo](swe-generate-and-transfer-a-bankgiro-payment-file-for-a-partially-used-credit-memo.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

