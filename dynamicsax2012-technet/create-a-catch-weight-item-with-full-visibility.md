---
title: Create a catch weight item with full visibility
TOCTitle: Create a catch weight item with full visibility
ms:assetid: a33510d3-b590-473f-9c4a-a5d152bfe184
ms:mtpsurl: https://technet.microsoft.com/library/Hh352316(v=AX.60)
ms:contentKeyID: 36687945
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a catch weight item with full visibility 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a catch weight item with full visibility. A catch weight item with full visibility requires that each unit of inventory is assigned a unique serial number and that the specific weight of the inventory unit is recorded. A unique serial number is associated with the weight of the inventory unit.


> [!NOTE]
> <P>When an item that is designated as a catch weight item is released, the designation can only be changed if you delete the item in all the companies where it exists.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane**, on the **Product** tab, in the **New** group, click **Product**. The **New released product** form is displayed.
    
    1.  In the **Identification** field group, enter the basic product information. For more information, see [Key tasks: Define products](key-tasks-define-products.md).
    
    2.  Select the **CW product** check box.
    
    3.  In the **Reference groups** field group, select values for the **Item model group**, the **Item group**, the **Storage dimension group**, and the **Tracking dimension group**.
        

        > [!NOTE]
        > <P>For a catch weight item with full visibility, you must specify a tracking dimension group where the serial number dimension and the serial number control are active.</P>
        > <UL>
        > <LI>
        > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Dimension groups</STRONG> &gt; <STRONG>Tracking dimension groups</STRONG>. Then select the <STRONG>Serial number control</STRONG> check box and select the <STRONG>Active</STRONG> check box on the <STRONG>Serial number</STRONG> line.</P></LI></UL>

    
    4.  In the **Units of measures** field group, select values for the **Inventory unit**, the **Purchase unit**, and the **Sales unit**.

3.  Click **OK** to return to the **Released products** list page.

4.  On the **Action Pane**, on the **Product** tab, in the **Set up** group, click **Unit conversions**.
    
    1.  Click **Inter-class conversions**, and then click **New**.
    
    2.  Enter values in the **Factor** field, the **From unit** field, and the **To unit** field.
    

    > [!NOTE]
    > <P>The nominal catch weight quantity is automatically calculated based on the unit conversion. This value appears in the <STRONG>Nominal quantity</STRONG> field on the <STRONG>Manage inventory</STRONG> FastTab in the <STRONG>Released product details</STRONG> form when you save the record or refresh the form. The nominal quantity is the actual weight of the item, not the standard weight or the theoretical weight.</P>



5.  Click **Close** to close the **Unit conversions** form.

6.  Double-click the catch weight item on the **Released products** list page. The **Released product details** form opens.

7.  On the **Manage inventory** FastTab in the **Catch weight** field group, enter details for the catch weight item:
    
    1.  In the **CW unit** field, select the catch weight unit of measure.
    
    2.  In the **Minimum quantity** field, enter the minimum amount of inventory for the product. This value must be less than the Nominal quantity.
    
    3.  In the **Maximum quantity** field, enter the maximum amount of inventory for the product. This value must be larger than the Nominal quantity
    
    4.  In the **Batch number group** field, enter a batch number group that has a Per quantity of zero.

## See also

[New released product (form)](https://technet.microsoft.com/library/hh597284\(v=ax.60\))

[Released product details (form)](https://technet.microsoft.com/library/aa615563\(v=ax.60\))

[Released products (list page)](https://technet.microsoft.com/library/hh597154\(v=ax.60\))

[Tracking dimension groups (form)](https://technet.microsoft.com/library/hh209465\(v=ax.60\))

  


