---
title: (SWE) Import BG Max payments to a payment journal
TOCTitle: (SWE) Import BG Max payments to a payment journal
ms:assetid: 0887d0e1-7094-46c8-94ec-63abc57eec8c
ms:mtpsurl: https://technet.microsoft.com/library/Gg230692(v=AX.60)
ms:contentKeyID: 36055973
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Sweden
---

# (SWE) Import BG Max payments to a payment journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can import Bankgiro (BG) Max payment files into Accounts receivable payment journals. BG Max is the format that is required to support Bankgiro Inbetalningar (Bankgiro Receivables). Bankgiro Inbetalningar (Bankgiro Receivables) is available from BankGiroCentralen, a payment provider in Sweden. Microsoft Dynamics AX supports the following versions of the BG Max payment files:

  - Basic/standard

  - Extended with OCR control of check number

  - Extended with OCR control of check number and length

  - Extended with OCR extended form registration control

Use the **Payment journal** form to import BG Max payment information to a payment journal.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal, and then click **Lines**.

3.  Click **Functions** \> **Import payments** to open the **Load diskette with payments** form.

4.  In the **Method of payment** field, select a method of payment that is set up to use the **Bankgiro Max (SE)** import format.

5.  Click **OK** to open the **Bankgirot Max (SE)** form.

6.  In the **File name** field, select the import file.

7.  To import incorrect records and correct them in the payment journal, select the **Import incorrect records** check box. Otherwise, clear the check box.

8.  Click **OK**. The payments are imported. For each payment, the following actions can occur:
    
      - If the payment has a corresponding invoice transaction in Microsoft Dynamics AX, it might be automatically marked for settlement in the payment journal.
    
      - If the payment and invoice amounts match, the payment can be posted.
    
      - If the payment amount is less than the invoice amount (underpayment), the amount remains as an open amount. You can view the amount in the **Customer transactions** form. If the payment amount is greater than the invoice amount (overpayment), a message is displayed. You must correct the payment in the payment journal before you can post it.

9.  Close the forms.


> [!NOTE]
> <P>If no payment records in the file match any invoices in Microsoft Dynamics AX, no transactions are imported, and an Infolog message is displayed. If only some of the records match, an Infolog message lists the amounts that were imported and the amounts that should have been imported.</P>



## See also

[(SWE) Set up a method of payment for BG Max payments](swe-set-up-a-method-of-payment-for-bg-max-payments.md)

  


