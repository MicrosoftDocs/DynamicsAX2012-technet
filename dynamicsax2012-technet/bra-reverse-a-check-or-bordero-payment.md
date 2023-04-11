---
title: (BRA) Reverse a check or Bordero payment
TOCTitle: (BRA) Reverse a check or Bordero payment
ms:assetid: 1a578448-2f88-4e93-81f9-41e36125ac2f
ms:mtpsurl: https://technet.microsoft.com/library/JJ910964(v=AX.60)
ms:contentKeyID: 53382659
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Reverse a check or Bordero payment 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can reverse a check or Bordero payment. When you reverse a payment, the transaction is canceled, and the related vendor invoices are available for settlement. If taxes were withheld from the check or Bordero payment, the withholding taxes are also reversed.

## Reverse a check

1.  Click **Cash and bank management** \> **Common** \> **Checks**.

2.  Select a check to reverse.

3.  On the **Action Pane**, click **Payment reversal** to open the **Payment reversal** form.

4.  In the **Date** field, specify the date on which to reverse the payment.

5.  In the **Reason code** field, select the reason for the reversal of the payment.
    

    > [!NOTE]
    > <P>You must specify the reason code if you selected the <STRONG>Require reasons for payment reversals</STRONG> check box in the <STRONG>Cash and bank management parameters</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/aa591289(v=ax.60)">Cash and bank management parameters (form)</A>.</P>



6.  In the **Reason comment** field, enter additional information about the reason for the reversal of the payment.

7.  Click **OK** to reverse the payment. The status of the check is updated to **Canceled** in the **Status** field in the **Checks** form.

## Reverse a Bordero payment

1.  Click **Cash and bank management** \> **Common** \> **Bordero**.

2.  Select a Bordero payment to reverse.

3.  On the **Action Pane**, click **Payment reversal** to open the **Payment reversal** form.

4.  In the **Date** field, specify the date on which to reverse the payment.

5.  In the **Reason code** field, select the reason for the reversal of the payment.
    

    > [!NOTE]
    > <P>You must specify the reason code if you selected the <STRONG>Require reasons for payment reversals</STRONG> check box in the <STRONG>Cash and bank management parameters</STRONG> form.</P>



6.  In the **Reason comment** field, enter additional information about the reason for the reversal of the payment.

7.  Click **OK** to reverse the payment. The status of the Bordero is updated to **Canceled** in the **Status** field in the **Bordero** form.

## See also

[(BRA) Payment reversals (modified form)](https://technet.microsoft.com/library/jj923375\(v=ax.60\))

[Reverse a posted check](reverse-a-posted-check.md)

  


