---
title: Set up subcodes for info codes (Retail essentials)
TOCTitle: Set up subcodes for info codes (Retail essentials)
ms:assetid: 87c57731-9467-4746-9e1e-b3502f17512c
ms:mtpsurl: https://technet.microsoft.com/library/Dn736911(v=AX.60)
ms:contentKeyID: 62200392
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up subcodes for info codes (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up subcodes for info codes. Subcodes present the point-of-sale (POS) cashier with responses to an info code. Subcodes are displayed either in a list or as buttons. The actions that are triggered by a subcode depend on the setup criteria.

For example, if you have an info code called “Return” that prompts the cashier to ask the customer why an item is being returned, you can use subcodes to track the customer’s response. For the “Return” info code, you might have subcodes for “Damaged, “Wrong size,” “Wrong style,” and “Not wanted.”

To set up subcodes for info codes, follow these steps:

1.  Click **Retail essentials** \> **Channels** \> **Setup** \> **POS** \> **Info codes**.

2.  In the **Info codes** form, in the left pane, select an info code that has an input type of **Subcode buttons** or **Subcode list**, and then click **Subcodes**.

3.  In the **Information subcodes** form, click **New** to create a subcode.

4.  In the **Subcode number** field, enter an identifier for the subcode.

5.  Optional: If you want a subcode to trigger an action, follow these steps:
    
    1.  In the **Trigger function** field, select whether the trigger function triggers an info code or a product, and then, in the **Trigger code** field, select the info code or the product number.
    
    2.  If you selected **Product** in the **Trigger function** field, specify the following information:
        
          - In the **Price type** field, select whether the price of the product is its regular price, a price that you specify, or a price that is reduced by a percentage.
        
          - In the **Amount / percent** field, enter a price for the product that is specified in the **Trigger code** field. Alternatively, if the price that is used at the point of sale reflects a price reduction, enter the percentage by which the price of the product is reduced.
    
    For example, when a customer buys a tennis racket, an info code could prompt the cashier to ask “Do you need tennis balls? They’re on sale this month.” When the cashier selects “Yes,” the discounted tennis balls are added to the transaction.
    
    To set this up, you would create a “Yes” subcode and a “No” subcode. Then, specify the following settings for the “Yes” subcode:
    
      - In the **Trigger function** field, select **Product**.
    
      - In the **Trigger code** field, select the item number of the tennis balls that are on sale.
    
      - In the **Price type** field, select **Price** for a specific sale price or select **Percent** for a percentage discount.
    
      - In the **Amount / percent** field, enter a sale price or discount percentage.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Set up info codes (Retail essentials)](set-up-info-codes-retail-essentials.md)

  


