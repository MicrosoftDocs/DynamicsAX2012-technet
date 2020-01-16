---
title: Set up a review process for reversals and cancellations
TOCTitle: Set up a review process for reversals and cancellations
ms:assetid: b18358cd-b48b-48ab-b8cd-2d97a741963d
ms:mtpsurl: https://technet.microsoft.com/library/Gg232393(v=AX.60)
ms:contentKeyID: 36058979
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a review process for reversals and cancellations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, reversals and cancellations are posted immediately when users click **Payment reversal** in the **Check** form or **Cancel payment** in the **Deposit slip** form. Use the following steps to send reversals and cancellations to journals for another user to review before the user approves and posts the reversal or cancellation, or rejects the reversal or cancellation.

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Select any of the following options:
    
      - To use the **Check reversals** review journal in Cash and bank management, select the **Use review process for payment reversals** check box.
    
      - To use the **Deposit slip payment cancellations** review journal in Cash and bank management, select the **Use review process for deposit slip payment cancellations** check box.
    
      - To require reason codes with payment reversals, select the **Require reasons for payment reversals** check box.
    
      - To require reason codes with cancellations, select the **Require reasons for deposit slip payment cancellations** check box.

3.  Close the form.

4.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

5.  Click **New** to create a journal name.
    
      - If you are creating a check-reversal journal name, select **Bank check reversal** in the **Journal type** field.
    
      - If you are creating a deposit-slip-cancellation journal name, select **Bank deposit slip cancellation** in the **Journal type** field.

6.  Press CTRL+S to save the journal name.

You can also set up alerts, so that reviewers are notified when records are ready for review. For more information, see [Create alert rules](create-alert-rules.md).

## See also

[Cash and bank management parameters (form)](https://technet.microsoft.com/library/aa591289\(v=ax.60\))

[Journal names setup (form)](https://technet.microsoft.com/library/aa552517\(v=ax.60\))

[Reverse a posted check](reverse-a-posted-check.md)

[Cancel a deposit slip payment](cancel-a-deposit-slip-payment.md)

[Check reversals lines (form)](https://technet.microsoft.com/library/hh209241\(v=ax.60\))

[Deposit slip payment cancellations lines (form)](https://technet.microsoft.com/library/hh242809\(v=ax.60\))

[Payment reversals (form)](https://technet.microsoft.com/library/hh208702\(v=ax.60\))

  


