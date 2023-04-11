---
title: (LVA) Create a payment order by using a vendor payment journal
TOCTitle: (LVA) Create a payment order by using a vendor payment journal
ms:assetid: f2ab85dc-488a-44fb-b019-fc92e42a18d9
ms:mtpsurl: https://technet.microsoft.com/library/JJ720371(v=AX.60)
ms:contentKeyID: 49721167
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Latvia
---

# (LVA) Create a payment order by using a vendor payment journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can create a payment order by using a vendor payment journal, you must set up a method of payment that includes any available export format. For more information, see [Set up payment types for vendor methods of payment](set-up-payment-types-for-vendor-methods-of-payment.md).

You must also create a payment specification code for the method of payment that you selected in the **Methods of payment - vendors** form. For more information, see [Vendor payment specification (form)](https://technet.microsoft.com/library/aa554108\(v=ax.60\)).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a journal, and then select a name.

3.  Click **Lines** to open the **Journal voucher** form, and then enter the required details.

4.  In the **Debit** field, enter a debit amount in the currency that is selected for the journal line.

5.  In the **Offset account type** field, select **Bank**.

6.  In the **Offset account** field, select a bank account that includes a payment order form.

7.  Select a method of payment that includes an export format.

8.  Select the payment specification for the method of payment that you selected.

9.  Click the **Payment** tab.

10. In the **Payer of bank commission** and **Foreign bank commission payer** fields, select who pays the bank commission:
    
      - **Payer** − The payer pays the commission to the bank.
    
      - **Receiver** − The receiver pays the commission to the bank.
    
      - **None** − No commission is paid to the bank.

11. Click **Post** \> **Post** to post the journal.

12. In the **Journal voucher** form, click **Print** \> **Print payment order** to open the **Approval of bank information** form.
    
    The fields that are displayed in the **Approval of bank information** form depend on the format of the payment order and the source of the transaction.

13. Click **OK** to print the payment order.

## See also

[(LVA) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/library/jj720361\(v=ax.60\))

[(LVA) Approval of bank information (form)](https://technet.microsoft.com/library/jj720366\(v=ax.60\))

  


