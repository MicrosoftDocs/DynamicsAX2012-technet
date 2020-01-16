---
title: (LVA) Create a payment order by using a customer payment journal
TOCTitle: (LVA) Create a payment order by using a customer payment journal
ms:assetid: 06bc0140-410a-46c1-99c5-5456bd4a3785
ms:mtpsurl: https://technet.microsoft.com/library/JJ720360(v=AX.60)
ms:contentKeyID: 49721156
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Latvia
---

# (LVA) Create a payment order by using a customer payment journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can create a payment order by using a customer payment journal, you must set up a method of payment that includes any available export format. For more information, see [Set up payment types for vendor methods of payment](set-up-payment-types-for-vendor-methods-of-payment.md).

You also must create a payment specification code for the method of payment that you selected in the **Methods of payment - customers** form. For more information, see [Customer payment specification (form)](https://technet.microsoft.com/library/aa620408\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a journal.

3.  Select a journal name.

4.  Click **Lines** to open the **Journal voucher** form, and then enter the required details.

5.  In the **Invoice** field, select the invoice number that is related to the payment.
    

    > [!NOTE]
    > <P>If multiple invoices are assigned, an asterisk (*) is displayed.</P>



6.  In the **Offset account type** field, select **Bank**.

7.  In the **Offset account** field, select a bank account that includes a payment order form.

8.  Select a method of payment that includes an export format.

9.  Click **Post** \> **Post** to post the journal.

10. In the **Journal voucher** form, click **Print** \> **Print payment order** to open the **Approval of bank information** form.
    
    The fields that are displayed in the **Approval of bank information** form depend on the format of the payment order and the source of the transaction.

11. Click **OK** to print the payment order.

## See also

[(LVA) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj720370\(v=ax.60\))

[(LVA) Approval of bank information (form)](https://technet.microsoft.com/library/jj720366\(v=ax.60\))

  


