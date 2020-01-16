---
title: (SWE) Generate and transfer a Bankgiro payment file for a partially used credit memo
TOCTitle: (SWE) Generate and transfer a Bankgiro payment file for a partially used credit memo
ms:assetid: 69a4c2e3-151d-4178-99df-122d829a55d7
ms:mtpsurl: https://technet.microsoft.com/library/Hh242608(v=AX.60)
ms:contentKeyID: 36057971
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Sweden
- Bankgirot
- credit memo
audience: Application User
ms.search.region: Sweden
---

# (SWE) Generate and transfer a Bankgiro payment file for a partially used credit memo 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In some instances, a credit memo that is sent to the Swedish payment clearing house, BankGiroCentralen (BGC), to settle a vendor payment contains an amount greater than the associated invoice. The vendor invoice is matched against the credit memo, and reported in the payment return file. When you import the payment return file, Microsoft Dynamics AX processes the partially used credit memo, without requiring manual steps.

Before generating a bank giro vendor payment file that contains vendor invoices and credit memos, you must:

  - Create, post, and transfer a credit note for a vendor through the invoice journal.

  - Create and post a vendor invoice. For more information, see [Post invoices in an invoice journal](post-invoices-in-an-invoice-journal.md) and [Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\)).

Use this procedure to generate and transfer a bank giro payment file.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new payment journal.

3.  In the **Name** field, select the journal name.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Press CTRL+N to create a new line and enter the required details.

6.  In the **Account type** field, select **Bank**.

7.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form. You can also click **Payment proposal** \> **Create payment proposal** to include vendor invoices or credit memos in the vendor payment file.

8.  Close the form to save your changes.

9.  Click the **General** tab, and in the **Currency** field, select the currency of the payment line.

10. Select the **Mark** check box for the credit memo line associated with the vendor invoice that you want to pay.

11. Click the **Payment** tab, and then in the **Method of payment** field, select the method of payment.
    

    > [!NOTE]
    > <P>You must set up bank giro SE as the method of payment in the <STRONG>Methods of payment - vendors</STRONG> form. For more information, see <A href="swe-set-up-a-method-of-payment-for-bankgirot-payments.md">(SWE) Set up a method of payment for Bankgirot payments</A>.</P>



12. Click the **Bank** tab, and then in the **Account identification** field, select the vendor's bank account identification.

13. Click the **Overview** tab, and then repeat steps 5 through 7.

14. Select the **Mark** check box for the credit memo line of the vendor credit invoice, and then repeat steps 9 through 12.

15. In the **Journal voucher** form, click **Functions** \> **Generate payments** to open the **Generate payments** form, and then enter the required details. For more information, see [Generate payments - vendor (class form)](https://technet.microsoft.com/library/aa586980\(v=ax.60\)).

16. Click **OK**. The vendor payment file is created and ready for submittal to BGC.
    
    The status of the payment journal line in the payment transfer journal is updated to **Sent**. Any invoices that you submit while the credit memo is under surveillance are matched and paid using the open credit memo. You cannot send a credit memo that is already under surveillance to BGC.

17. Close the forms to save your changes.

## See also

[(SWE) Import and post a payment return file for a partially used credit memo](swe-import-and-post-a-payment-return-file-for-a-partially-used-credit-memo.md)

  


