---
title: (IND) Create service orders manually
TOCTitle: (IND) Create service orders manually
ms:assetid: e8cd47e7-ce2e-4939-9d6c-5351e51e9fad
ms:mtpsurl: https://technet.microsoft.com/library/JJ710921(v=AX.60)
ms:contentKeyID: 49386333
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create service orders manually 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create service orders manually from a service agreement or from a project.

You can also use automated processes to create service orders. For more information, see [Create service orders automatically](create-service-orders-automatically.md).

1.  Click **Service management** \> **Common** \> **Service orders** \> **Service orders**. On the **Action Pane**, click **Service order**.
    
    –or–
    
    Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**. Open a service agreement. In the **Service agreements** form, on the **Action Pane**, on the **Deliver** tab, click **Planned service orders**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a project. In the **Projects** form, on the **Action Pane**, on the **Manage** tab, click **Service** \> **Service order**.
    

    > [!NOTE]
    > <P>If you create a service order from the <STRONG>Projects</STRONG> form, the project identifier and customer information are automatically added to the service order.</P>



2.  In the **Create service orders** form, on the **General** tab, select the starting and ending dates for the order.

3.  Enter the applicable information in the remaining fields, and then click **OK**. For more information about how to complete the information in the form, see [Create service orders (class form)](https://technet.microsoft.com/library/aa553901\(v=ax.60\)).

4.  In the **Service orders** form, in the **Line view**, on the **General** FastTab, in the **Service agreement** field, you can select a service agreement for the service order.

5.  On the **Lines** FastTab, select the **Hour**, **Expense**, **Item**, or **Fee** transaction type. The information on the **Line details** FastTab depends on the transaction type that you select.
    
      - For an **Hour** transaction type, on the **Prices** tab, enter the sales tax information, number of hours, cost price per hour, sales price per hour, and total assessable value of the transaction.
    
      - For an **Expense** transaction type, on the **Prices** tab, enter the sales tax information, quantity, cost price, sales price, and total assessable value for the expense. You must also select the financial account that is reduced by the amount that you add to the service order.
    
      - For an **Item** transaction type, on the **Prices** tab, the quantity, cost, and price information are automatically added from the sales order line. You can change these values.
        
        For an **Item** transaction type, on the **Tax information** tab, enter the tax codes and other tax information for the item transaction.
        

        > [!NOTE]
        > <P>The <STRONG>Tax information</STRONG> tab is available only if you select an <STRONG>Item</STRONG> transaction type on the <STRONG>Lines</STRONG> FastTab.</P>



6.  Complete the information in the remaining fields for the sales order. For more information, see [(IND) Service orders (modified form)](https://technet.microsoft.com/library/jj678027\(v=ax.60\)).

## See also

[Service orders (form)](https://technet.microsoft.com/library/aa554361\(v=ax.60\))

[Create service orders automatically](create-service-orders-automatically.md)

  


