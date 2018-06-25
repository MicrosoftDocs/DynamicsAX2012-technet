---
title: Set up commodity cost basis pricing for a pricing calculation
TOCTitle: Set up commodity cost basis pricing for a pricing calculation
ms:assetid: 5d63053c-a829-4a03-95bc-427ca25ace43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209124(v=AX.60)
ms:contentKeyID: 36057577
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up commodity cost basis pricing for a pricing calculation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up the cost basis for a pricing calculation.


> [!NOTE]
> <P>If this is the first time that you set up the cost basis for a pricing calculation, enter the costing information for each item that uses this pricing calculation. If the item is included in any future pricing calculations of this combination, the initial costing information is used as the default information. However, you can change the costing information.</P>



1.  Click **Inventory management** \> **Periodic** \> **Commodity pricing** \> **Pricing calculation**.

2.  Select the pricing calculation that you want to set up with cost basis pricing.

3.  Click the **Commodity pricing** button.

4.  In the **Item number** field, select the item number for which the commodity cost pricing information is added.

5.  In the **Site** field, select the site for the item, if applicable.

6.  In the **Warehouse** field, select the warehouse where the item is located. If you do not specify a warehouse, the value in the **New cost** field is used for all warehouses where the item is maintained.

7.  Select the **Active cost price** check box if the active cost price for the item is used for the specified warehouse, or for all warehouses if you do not specify one.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Active cost price</STRONG> check box or you select a base item in the <STRONG>Base item</STRONG> field, the <STRONG>New cost</STRONG> field is display only.</P>



8.  If the cost basis for the item uses the cost basis of a base item that is predefined, select the item in the **Base item** field. Then select a site and warehouse, if applicable, in the corresponding **Base site** and **Base warehouse** fields.

9.  If you select a base item in the **Base item** field:
    
      - Calculate the difference between the **New cost** and the **Previous cost** for the base item and the warehouse of the base item.
    
      - Enter the difference in the **Price plus** field or the **Price plus percentage** field. The value in the **New cost** field is then calculated. For more information, see [Commodity pricing (form)](https://technet.microsoft.com/en-us/library/hh242855\(v=ax.60\)).
    
      - Enter the price multiplier used in the automatic calculation of the **New cost** in the **Price multiplier** field.

## See also

[About commodity pricing](about-commodity-pricing.md)

[Commodity pricing (form)](https://technet.microsoft.com/en-us/library/hh242855\(v=ax.60\))

[Pricing calculation (form)](https://technet.microsoft.com/en-us/library/hh209660\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

