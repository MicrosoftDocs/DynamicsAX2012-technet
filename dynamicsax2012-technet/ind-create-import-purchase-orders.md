---
title: (IND) Create import purchase orders
TOCTitle: (IND) Create import purchase orders
ms:assetid: c6ddaa6a-a7ba-4505-96fe-d3059a211349
ms:mtpsurl: https://technet.microsoft.com/library/JJ664898(v=AX.60)
ms:contentKeyID: 49386227
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create import purchase orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Create purchase order** form to create an import order for a vendor. Select the **Import order** check box only when **Purchase order** is selected in the **Purchase order** field.

You can modify the default values of the sales tax group and the item sales tax group for a vendor in the **Sales tax group** field and **Item sales tax group** field on the **Setup** tab in the lower pane of the **Purchase order** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order.

2.  Press CTRL+N to create a new purchase order.

3.  In the **Create purchase order** form, select the vendor account in the **Vendor account** field.
    

    > [!NOTE]
    > <P>For more information about how to create a purchase order, see <A href="create-a-purchase-order.md">Create a purchase order</A>.</P>



4.  Select the type of purchase order in the **Purchase order** field.

5.  Select the **Import order** check box to create an import order for the vendor.
    

    > [!NOTE]
    > <P>If the vendor that you selected is a foreign vendor and the <STRONG>Purchase order</STRONG> is selected in the <STRONG>Purchase order</STRONG> field, the <STRONG>Import order</STRONG> check box is selected automatically.</P>



6.  Enter the required details and click **OK** to create the import purchase order.

7.  In the **Purchase order** form, press CTRL+N to create new lines for the import items on the **Lines** tab. Enter the required details.

8.  Click the **Setup** tab in the lower pane to modify the **Sales tax group** and **Item sales tax group** fields.

9.  Click the **Price and discount** tab in the lower pane. The maximum retail price defined for the item is displayed in the **Max. retail price** field. The maximum retail price in customs currency is displayed in the **Max. retail price in customs currency** field, and can be modified.
    

    > [!NOTE]
    > <P>If you modify the maximum retail price amount in the <STRONG>Max. retail price in customs currency</STRONG> field, the amount in the <STRONG>Max. retail price</STRONG> field is updated automatically in transaction currency.</P>



10. Click the **Tax information** tab. The IEC number attached to the company address is displayed in the **IEC number** field.

11. Select the ECC number in the **ECC number** field and the excise record type in the **Excise record type** field.
    

    > [!NOTE]
    > <P>You can select the tax code for an excise tax type for the selected Excise control code (ECC) number in the <STRONG>Apply excise</STRONG> field. Select the tax code only if additional customs duty for excise must be paid on the imported items.</P>

    
    Additional customs duty for excise is paid only on the import orders. The customs tariff code defined for the item is displayed in the **Customs tariff code** field.

12. Press CTRL+S or close the form.

## See also

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\))

[(IND) Create purchase order (modified form)](https://technet.microsoft.com/library/jj664490\(v=ax.60\))

  


