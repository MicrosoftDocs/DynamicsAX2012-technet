---
title: (RUS) Prepayments in Retail for Russia
TOCTitle: (RUS) Prepayments in Retail for Russia
ms:assetid: c5588433-d198-4a3f-9a12-3c79a4293f06
ms:mtpsurl: https://technet.microsoft.com/library/Dn268486(v=AX.60)
ms:contentKeyID: 54917025
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransRDeferrals
- RU - 00037
- RU – 00019
- MsDynAx060.Forms.LedgerJournalTransRDeferrals
audience: Application User
ms.search.region: Russia
---

# (RUS) Prepayments in Retail for Russia 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The following information describes how Microsoft Dynamics AX processes prepayment transactions for the following payment types in Retail:

  - **Customer account deposit payment** – A customer makes a prepayment at the Retail point of sale (POS). Microsoft Dynamics AX processes the deposit payment as a prepayment transaction. When you post the transaction, a payment journal is posted in the **Journal voucher** form. The **Prepayment journal voucher** check box on the **Payment** tab in the **Journal voucher** form is automatically selected for the payment journal. For more information about the other fields in the form, see [(RUS) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj733240\(v=ax.60\)).

  - **Customer order with deposit** – A customer provides a customer order at the Retail POS. The customer can deposit a payment for the order based on the parameters that you have set up in the **Retail parameters** form. Microsoft Dynamics AX processes the deposit payment for the customer order as a prepayment transaction. When you post the transaction, a customer payment journal is created and posted in the **Journal voucher** form. The **Prepayment journal voucher** check box on the **Payment** tab in the **Journal voucher** form is automatically selected for the payment journal. The payment is settled and the customer invoice is issued automatically when the order is picked up or delivered.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 1 for AX 2012 R2.</P>



Microsoft Dynamics AX performs the following tasks to process a prepayment:

  - **Processes a customer account deposit payment** – The payment that the customer deposits, is transferred to Microsoft Dynamics AX using a service that synchronizes data. Microsoft Dynamics AX creates a retail payment transaction for the payment. When you post the retail transaction, a cash journal or customer payment journal is posted. The **Prepayment journal voucher** check box on the **Payment** tab in the **Journal voucher** form is automatically selected for the payment journal. You cannot process the prepayments if the payment amount is negative.

  - **Processes a customer order with a deposit** – The customer makes a required deposit for a customer order using the Real-time service. Whether Microsoft Dynamics AX creates a customer payment journal or a cash journal depends on the method of payment that the customer uses. The **Prepayment journal voucher** check box on the **Payment** tab in the **Journal voucher** form is automatically selected for the journal. If the customer makes partial payments by using multiple methods of payment, Microsoft Dynamics AX processes each partial payment by using the method of payment for that partial payment.
    
    When you cancel a customer order, the prepayment amount is refunded and a refund payment journal is posted for the deposit amount. The refund amount is calculated and posted based on the method of payment that you specify when you post the refund payment. Microsoft Dynamics AX may apply a cancellation charge based on the parameters that you set in the **Retail parameters** form. For more information about the fields in the form, see [Retail parameters (form)](https://technet.microsoft.com/library/hh597194\(v=ax.60\)).
    
    When you return a customer order, a return order and a refund payment journal are created. When you post the return order, Microsoft Dynamics AX creates a customer payment journal or a cash journal. The type of journal that is created depends on the method of payment that is used by the customer for the original transaction.

  


