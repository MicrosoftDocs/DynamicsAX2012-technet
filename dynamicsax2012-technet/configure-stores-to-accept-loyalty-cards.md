---
title: Configure stores to accept loyalty cards
TOCTitle: Configure stores to accept loyalty cards
ms:assetid: 609728de-6d4d-438a-8251-37cfc6d48191
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597107(v=AX.60)
ms:contentKeyID: 39519156
ms.date: 04/25/2014
mtps_version: v=AX.60
---

# Configure stores to accept loyalty cards 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Before a store can participate in a customer loyalty program, you must set up the store to accept a loyalty card. Some stores might not support a loyalty program.

Before you can set up a store to accept a loyalty card, you must set up the loyalty card as a payment method. For more information about how to set up a loyalty card as a payment method, see [Set up loyalty payment methods](set-up-loyalty-payment-methods.md).

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select a store in the list. Alternatively, you can create a new store by clicking **Retail store** on the **Action Pane**.

3.  Click the **Set up** tab, and then, on the **Action Pane**, in the **Set up** group, click **Payment methods**.

4.  In the **Payment method** form, click **New** to create a new payment method.

5.  On the **General** FastTab, in the **Payment method** field, select the tender that you created for the loyalty card.

6.  In the remaining fields in the **Payment method** form, enter the information that is required for the store. For more information about how to configure payment methods for a store, see [Set up store payment methods](set-up-store-payment-methods.md).

7.  In the **Payment method** form, on the **Action strip**, click **Card setup**.

8.  In the **Card setup** form, click **New** to add a new loyalty card number.

9.  On the **General** FastTab, do the following:
    
      - In the **Card ID** field, select the loyalty card that you set up.
    
      - Enter a name for the card type.
    
      - Select the **Allow manual approval codes** check box to indicate that a cashier can manually enter a loyalty card number if the card cannot be read correctly.
    
      - Select the **Process locally** check box to indicate that your company uses an internal loyalty transaction service.
    
      - Enter any other requirements that the store has for the loyalty program.

## See also

[About setting up loyalty programs](about-setting-up-loyalty-programs.md)

[Set up loyalty payment methods](set-up-loyalty-payment-methods.md)

[Stores (form)](https://technet.microsoft.com/en-us/library/hh580646\(v=ax.60\))

[Card setup (form)](https://technet.microsoft.com/en-us/library/hh597124\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

