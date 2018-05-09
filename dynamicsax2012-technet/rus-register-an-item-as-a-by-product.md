---
title: (RUS) Register an item as a by-product
TOCTitle: (RUS) Register an item as a by-product
ms:assetid: 919736c4-39e5-494c-9689-a9657ee2c5d0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678479(v=AX.60)
ms:contentKeyID: 49387708
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Register an item as a by-product 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **By-product** form to register an item that is generated as a by-product during the production cycle. By-products are included when the cost of the production order is calculated.

1.  Click **Inventory management** \> **Setup** \> **By-product**.

2.  Create a by-product. For more information, see [Create a by-product](create-a-by-product.md).

3.  In the **Main product** field, select the item number of the primary product.

4.  In the **By-product** field, select the item number of the by-product.

5.  In the **Costing rule** field, select the cost calculation rule that is used to calculate the cost of by-products. The following options are available:
    
      - **Fixed price** – The cost of the by-product is calculated based on the price that you entered in the **Released product details** form when you create an item as a by-product.
    
      - **Calculated price** – The cost of the by-product is calculated as a percentage of the production cost, based on the percentage that you enter in the **Percent** field.

6.  In the **Percent** field, enter the percentage that is used to calculate the cost price.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Calculated price</STRONG> in the <STRONG>Costing rule</STRONG> field.</P>



## See also

[(RUS) By-product (form)](https://technet.microsoft.com/en-us/library/jj711526\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

