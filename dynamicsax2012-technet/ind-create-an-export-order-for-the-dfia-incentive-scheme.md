---
title: (IND) Create an export order for the DFIA incentive scheme
TOCTitle: (IND) Create an export order for the DFIA incentive scheme
ms:assetid: 363394e0-55ba-4cc8-b94e-fc03456c2176
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664615(v=AX.60)
ms:contentKeyID: 49385692
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- customs incentive scheme
- EXIM incentive scheme
- export order
- India customs
- incentive scheme
- DFIA
- Duty Free Import Authorization
- customs export
- DFIA incentive scheme
---

# (IND) Create an export order for the DFIA incentive scheme 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can attach the authorization number for a Duty Free Import Authorization (DFIA) to an export order. By doing this, you can track the export obligation for which the input goods were imported under the DFIA scheme.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. On the **Action pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

2.  In the **Create sales order** form, in the **Customer account** field, select the customs customer, and then select the **Export order** check box.

3.  Enter any additional information, and then click **OK** to create a new sales order.
    
    For more information about how to create a sales order, see [(IND) Create an export sales order and post the confirmation order](ind-create-an-export-sales-order-and-post-the-confirmation-order.md). For information about India-specific fields in the **Sales order** form, see [(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\)).

4.  Add a sales order line, and then, at the bottom of the **Line details** FastTab, click the **Setup** tab.

5.  In the **Sales tax** field group, select the sales tax group and the item sales tax group.

6.  At the bottom of the **Line details** FastTab, click the **Tax information** tab.

7.  In the **Customs** field group, in the **Customs tariff code** field, select the customs tariff code for the sales order line.

8.  In the **EXIM incentive scheme** field group, select the incentive scheme group, the EXIM port ID, and the product group for the export order.
    

    > [!TIP]
    > <P>After you complete this step, you can view information about the export obligation, the amount of the export obligation that has been fulfilled, and the remaining export obligation balance in the <STRONG>Export obligation</STRONG> form. On the <STRONG>Sales order lines</STRONG> FastTab, click <STRONG>Product and supply</STRONG>, and then click <STRONG>EXIM - DFIA</STRONG>.</P>



9.  Add another sales order line or, if the sales order is complete, confirm the sales order and post the invoice. For more information, see [(IND) Create an export sales order and post the confirmation order](ind-create-an-export-sales-order-and-post-the-confirmation-order.md).

After you create and post the export sales order, create and post the shipping bill for the order by using the procedure in [(IND) Post a shipping bill for an export sales order](ind-post-a-shipping-bill-for-an-export-sales-order.md).

## See also

[(IND) Create an export sales order and post the confirmation order](ind-create-an-export-sales-order-and-post-the-confirmation-order.md)

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

[(IND) Post a shipping bill for an export sales order](ind-post-a-shipping-bill-for-an-export-sales-order.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

