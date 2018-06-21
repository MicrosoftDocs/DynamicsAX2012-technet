---
title: (CHE) Import ESR payment information to a payment journal
TOCTitle: (CHE) Import ESR payment information to a payment journal
ms:assetid: fc7774eb-65e4-491d-aa88-3bc6597d4963
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243307(v=AX.60)
ms:contentKeyID: 36060093
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CHE) Import ESR payment information to a payment journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Payment journal** form to import Enzahlungsschein mit Referenznummer (ESR) payment information to a payment journal.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal, and then click **Lines**.

3.  In the **Journal voucher** form, click **Functions** \> **Import payments**.

4.  In the **Load diskette with payments** form, select a method of payment that is set up to use the **ESR (CH)** import format.

5.  Click **OK**. The payments are imported.

6.  Close the forms to save your changes.

For each direct debit payment that was processed through the Lastschriftenverfahren (LSV) system and that uses Swiss francs (CHF) as the currency, the following processes take place:

  - The original LSV payment line is unsettled and the status is set to **Rejected**.

  - The ESR number is matched to the corresponding invoice and can be automatically settled.


> [!NOTE]
> <P>If some of the LSV payments are not processed, some open payment lines will remain in the LSV journal. This can happen if the customer bank account has a low balance. To post the remaining open payment lines in the LSV journal, you must first delete the rejected payment lines.</P>



## See also

[(CHE) Swiss LSV+ electronic payment format](che-swiss-lsv-electronic-payment-format.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

