---
title: Set up payment schedules on orders
TOCTitle: Set up payment schedules on orders
ms:assetid: 52c7d5b7-a86f-41bb-8f8c-a3159f2ac601
ms:mtpsurl: https://technet.microsoft.com/library/Aa548920(v=AX.60)
ms:contentKeyID: 43976716
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up payment schedules on orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You and a customer or vendor might agree to pay one invoice by using a series of installment payments based on a predefined payment schedule. The **Payment schedule** configuration key must be selected before you can set up a payment schedule for an order.

When an invoice that has a payment schedule is posted, a separate invoice line transaction is created, based on the due date for each line of the payment schedule. The original sales transaction or purchase transaction remains unchanged, and several open payment transactions are linked to the original transaction. You can view information about each invoice line in the **Settle open transactions** form.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click an order or create an order.

3.  On the **Action Pane**, click **Header view**.

4.  Click the **Price and discount** FastTab, and then select a payment schedule for the order.

5.  To view or modify the date or amount of each payment, on the **Action Pane**, click the **Invoice** tab, and then click **Payment schedule**.

6.  On the **Payment schedule** tab, you can change the allocation method, and then click **Calculate** to recalculate the lines. If you select the **Fixed amount** allocation method, rounding amounts or remaining amounts are included with the last payment.
    

    > [!NOTE]
    > <P>Alternatively, on the <STRONG>Payment lines</STRONG> tab, you can modify each installment.</P>



## See also

[Create a purchase order](create-a-purchase-order.md)

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

[Purchase order (form)](https://technet.microsoft.com/library/aa557983\(v=ax.60\))

  


