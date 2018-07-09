---
title: Create a catch weight item with partial visibility
TOCTitle: Create a catch weight item with partial visibility
ms:assetid: c479528a-c743-44ed-850d-6f6575ef0478
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352345(v=AX.60)
ms:contentKeyID: 36687976
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a catch weight item with partial visibility [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a catch weight item with partial visibility. For a catch weight item with partial visibility, one or more units of inventory use the same serial number or batch number. Only the aggregate of the values in the inventory unit is recorded. The values for individual units that share the same batch or serial number do not have to be recorded. As a result, the value in the inventory unit must be entered for each transaction that includes the inventory unit.


> [!NOTE]
> <P>When an item that is designated as a catch weight item is released, the designation can only be changed if you delete the item in all the companies where it exists.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, on the **Product** tab, in the **New** group, click **Product**. The **New released product** form opens.
    
    1.  In the **Identification** field group, enter the basic product information. For more information, see [Key tasks: Define products](key-tasks-define-products.md).
    
    2.  Select the **CW product** check box.
    
    3.  In the **Reference groups** field group, select values for the **Item model group**, the **Item group**, and the **Storage dimension group**.
    
    4.  In the **Units of measures** field group, select values for the **Inventory unit**, the **Purchase unit**, and the **Sales unit**.

3.  Click **OK** to return to the **Released products** list page.

4.  On the **Action Pane**, on the **Product** tab, in the **Set up** group, click **Unit conversions**.
    
    1.  Click **Inter-class conversions**, and then click **New**.
    
    2.  Enter values in the **Factor** field, the **From unit** field, and the **To unit** field.
    

    > [!NOTE]
    > <P>The nominal catch weight quantity is calculated based on the unit conversion. This value appears in the <STRONG>Nominal quantity</STRONG> field on the <STRONG>Manage inventory</STRONG> FastTab in the <STRONG>Released product details</STRONG> form when you have saved the record or refreshed the form. The nominal quantity is the actual weight of the item, not the standard weight or the theoretical weight.</P>



5.  Click **Close** to close the **Unit conversions** form.

6.  Double-click the catch weight item on the **Released products** list page. The **Released product details** form opens.

7.  On the **Manage inventory** FastTab in the **Catch weight** field group, enter details for the catch weight item:
    
    1.  In the **CW unit** field, select the catch weight unit of measure.
    
    2.  In the **Minimum quantity** field, enter the minimum amount of inventory allowed for the product. This value must be less than the Nominal quantity.
    
    3.  In the **Maximum quantity** field, enter the maximum amount of inventory for the product. This value must be larger than the Nominal quantity
    
    4.  In the **Batch number group** field, enter a batch number group that has a Per quantity of zero.

## See also

[New released product (form)](https://technet.microsoft.com/en-us/library/hh597284\(v=ax.60\))

[Released product details (form)](https://technet.microsoft.com/en-us/library/aa615563\(v=ax.60\))

[Released products (list page)](https://technet.microsoft.com/en-us/library/hh597154\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

