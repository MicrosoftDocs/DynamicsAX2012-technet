---
title: Process an authorization for a sales order
TOCTitle: Process an authorization for a sales order
ms:assetid: 793bbf11-d089-4280-afdf-6640e3cbdd87
ms:mtpsurl: https://technet.microsoft.com/library/Gg213014(v=AX.60)
ms:contentKeyID: 36655935
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Process an authorization for a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to verify the credit card number and available balance when a credit card is submitted for the payment of a sales order. You must have set up a payment service, such as Payment Services for Microsoft Dynamics ERP, before you can complete this procedure.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action Pane**, in the **New** group, click **Sales order**.

2.  Select a customer account, and then click **OK**.

3.  Enter information about the sales order and lines.

4.  On the **Action Pane**, click **Header view**.

5.  On the **Price and discount** FastTab, in the **Payment** field, select terms of payment that have a credit card payment type.
    

    > [!NOTE]
    > <P>The bank that is specified for the method of payment must use the same currency that the credit card uses. Other than this, the method of payment is not used for credit card payments.</P>



6.  Enter or select a credit card number.

7.  On the **Action Pane**, click the **Manage** tab. In the **Customer** group, click **Credit card** \> **Authorize**.

8.  If required, enter the three- or four-digit credit card verification value that is printed on the credit card.

9.  When the authorization process is complete, a message is displayed which informs you whether the credit card is authorized. In addition, the sales order is updated with the result of the authorization attempt.
    

    > [!TIP]
    > <P>To view information about the authorization for a sales order, click <STRONG>Credit card</STRONG> &gt; <STRONG>Authorization history</STRONG> in the <STRONG>Sales order</STRONG> form.</P>



## See also

[About credit card authorizations](about-credit-card-authorizations.md)

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

  


