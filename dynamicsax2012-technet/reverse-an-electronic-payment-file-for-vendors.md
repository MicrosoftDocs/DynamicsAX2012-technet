---
title: Reverse an electronic payment file for vendors
TOCTitle: Reverse an electronic payment file for vendors
ms:assetid: 048cbcce-dee4-4b39-ba49-6b2cb199bbb4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn375765(v=AX.60)
ms:contentKeyID: 56348877
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Reverse an electronic payment file for vendors 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to correct the balances for an electronic payment that has already been settled. You cannot reverse a payment to undo it. Instead, you must reverse the settlement, create a negative payment, and then settle the negative payment with the original payment.

## Reverse the settlement

To reverse the settlement, follow these steps:

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor.

3.  On the **Action Pane**, on the **Invoice** tab, click **Closed transaction editing**.

4.  In the **Closed transaction editing in several currencies** form, select the payment, and then click **Reverse**. The settlement between the electronic payment and the invoice is reversed.

## Create a negative payment (credit amount) and settle it with the original payment

To create a negative payment and settle it with the original payment, follow these steps:

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Enter a journal name, and then click **Lines**.

3.  Create a negative payment (credit amount) in the vendor payment journal. The negative payment must have the same amount, payment method, and bank account as the original, incorrect payment.

4.  Click **Functions** \> **Settlement**. Settle the negative payment against the original debit value payment, and then post it.
    
    In Cash and bank management, the bank account balance is correct. In Accounts payable, the original invoice is available to be settled with a different payment.

## See also

[Create an electronic payment file for vendors](create-an-electronic-payment-file-for-vendors.md)

[Reverse settlements](reverse-settlements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

