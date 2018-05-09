---
title: (IND) Update the import order line quantity after updating the invoice registration
TOCTitle: (IND) Update the import order line quantity after updating the invoice registration
ms:assetid: dcd78907-9c94-4c60-b51d-6367ea1b8c0c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710884(v=AX.60)
ms:contentKeyID: 49386297
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- India
- import order line quantity
- invoice registration
- order line quantity
- Update the import order line
---

# (IND) Update the import order line quantity after updating the invoice registration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create an import order for a vendor by selecting the **Import order** check box in the **Create purchase order** form.

You can modify the sales tax group and item sales tax group that are used by default for a vendor. Update the values in the **Sales tax group** and **Item sales tax group** fields on the **Setup** tab in the lower pane of the **Purchase order** form.


> [!NOTE]
> <P>On the <STRONG>Setup</STRONG> tab, in the <STRONG>Apply excise</STRONG> field, you can select the tax code that is used for a type of excise tax for the selected Excise control code (ECC) number. Select the tax code only if additional customs duty for excise must be paid on the imported items.</P>



Use the following procedure to update the quantity of an item on the purchase order after the item has been updated in the **Invoice registration** form.


> [!NOTE]
> <P>When the quantity of an item is updated, the new quantity can be more than the quantity that was specified in the <STRONG>Invoice registration</STRONG> form for the item.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order that is an import order.

3.  On the **Action Pane**, on the **Customs** tab, click the **Invoice registration** button to open the **Invoice registration** form.

4.  Update the **Receive** field for an item to the correct quantity.
    

    > [!NOTE]
    > <P>The new quantity in the <STRONG>Receive</STRONG> field must not be less than the quantity that is posted for the item in the <STRONG>Bill of entry</STRONG> form. The total quantity that is updated for the item cannot be more than the item’s quantity on the import order.</P>



## See also

[(IND) Bill of entry journal (form)](https://technet.microsoft.com/en-us/library/jj677988\(v=ax.60\))

[(IND) Set up a bill of entry number for import orders](ind-set-up-a-bill-of-entry-number-for-import-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

