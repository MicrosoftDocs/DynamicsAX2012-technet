---
title: (IND) Create an export sales order and post the confirmation order
TOCTitle: (IND) Create an export sales order and post the confirmation order
ms:assetid: 55f3b2c8-c233-4612-a8d9-9704f9f6c058
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677823(v=AX.60)
ms:contentKeyID: 49385785
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales order
- (IND)
- India
- confirmation order
- export sales order
---

# (IND) Create an export sales order and post the confirmation order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can apply for an Advance Authorization (AA) tax incentive, create and confirm an export sales order, export the order, and record annual consumption. Use this procedure to create an export sales order and post the confirmation order.

## Create an export sales order

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **All sales orders** list page, on the **Action pane**, on the **Sales order** tab, click **Sales order** to create a new sales order.

3.  In the **Create sales order** form, in the **Customer account** field, select the customs customer. Then select the **Export order** check box.

4.  Select the **DSA** check box.
    

    > [!NOTE]
    > <P>The <STRONG>DSA</STRONG> check box can be selected only for released products that have <STRONG>Production</STRONG> selected in the <STRONG>Default order type</STRONG> field on the <STRONG>Default order settings</STRONG>.</P>



5.  Enter any additional field values, and then click **OK** to create a new sales order.

6.  In the **Sales order** form, on the **Sales order lines** FastTab, add a sales order line for an item that is included in a bill of material (BOM) or BOM version.
    
    For more information about how to create an item that is included in a BOM, see [Create a BOM and BOM version](create-a-bom-and-bom-version.md).

7.  On the **Line details** FastTab, click the **Tax information** tab in the lower pane.

8.  In the **Port ID** field, select the export-import (EXIM) port for the sales order.
    
    In the **Product group** field, select the product group that applies to the items in the export order.

## Post the confirmation order

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **All sales orders** list page, open the sales order to post the confirmation order for.

3.  In the **Sales order** form, on the **Action Pane**, click the **Sell** tab. Then, in the **Generate** group, click **Sales order confirmation**.

4.  In the **Confirm sales order** form, in the upper pane, on the **Parameters** tab, in the **Parameter** group, select the **Posting** check box. To print the confirmation order, in the **Print options** group, set your print options and select the **Print confirmation** check box.

5.  Click **OK** to post the confirmation order. If you selected print options, the confirmation order also is printed.

6.  To verify and confirm the sales order details, in the **Sales order** form, on the **Action Pane**, click the **Sell** tab. Then, in the **Journals** group, click **Sales order confirmation**.
    

    > [!NOTE]
    > <P>The <STRONG>Port ID</STRONG>, <STRONG>Product group</STRONG>, and <STRONG>Assessable value</STRONG> fields in the <STRONG>Sales order confirmations</STRONG> form are updated with the port ID, product group, and assessable value that are selected on the line item when the confirmation journal is posted.</P>



## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

[(IND) About the EXIM Advance Authorization (AA) incentive scheme](ind-about-the-exim-advance-authorization-aa-incentive-scheme.md)

[(IND) Create EXIM authorization schemes for confirmed sales orders](ind-create-exim-authorization-schemes-for-confirmed-sales-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

