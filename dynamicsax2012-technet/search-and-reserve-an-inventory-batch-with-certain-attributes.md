---
title: Search and reserve an inventory batch with certain attributes
TOCTitle: Search and reserve an inventory batch with certain attributes
ms:assetid: dabc91cd-e135-4546-add5-ec9c2279a56e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh328583(v=AX.60)
ms:contentKeyID: 36688005
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Search and reserve an inventory batch with certain attributes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to search for an inventory batch with certain attributes, and then reserve the inventory to a sales order.


> [!NOTE]
> <P>From the <STRONG>Batch attribute search</STRONG> form, you can create a template based on the search criteria that you set up in the form. For more information, see <A href="create-a-batch-attribute-search-template.md">Create a batch attribute search template</A>. To retrieve search criteria from a template, click <STRONG>Get template</STRONG> in the <STRONG>Batch attribute search</STRONG> form.</P>



1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Double-click the sales order for which inventory is being reserved. The **Sales order** form is displayed.

3.  On the **Sales order lines** FastTab, select the sales order line for the item to be reserved.
    

    > [!NOTE]
    > <P>The item you select must be batch controlled. An item is batch controlled if the batch number dimension is active on the item's tracking dimension group.</P>
    > <UL>
    > <LI>
    > <P>Click <STRONG>Product information management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Dimension groups</STRONG> &gt; <STRONG>Tracking dimension groups</STRONG>. Then select the <STRONG>Active</STRONG> check box for the <STRONG>Batch number</STRONG> line.</P></LI></UL>



4.  Click **Inventory** and then select **Batch reservation**.

5.  In the **Batch reservation** form, click **Batch attribute search**. The **Batch attribute search** form opens with default criteria for batch attributes by item.
    
      - To change the criteria to batch attributes by item and customer, click **Customer attributes**.
    
      - To refine the search, change the values in the **Attribute** and **Operator** fields.
    
      - To add a new line of search criteria, press CTRL+N and then enter the values.

6.  Click **OK** to initiate the search. When the search is complete, the **Batch reservation** form opens again with the search results.

7.  In the **Reservation** field, enter the quantity to be reserved to the sales order. For a catch weight item, use the **CW reservation** field.

## See also

[About batch attributes](about-batch-attributes.md)

[Batch attribute search (form)](https://technet.microsoft.com/en-us/library/hh242819\(v=ax.60\))

[Batch reservation (form)](https://technet.microsoft.com/en-us/library/hh208645\(v=ax.60\))

[Sales orders (form)](https://technet.microsoft.com/en-us/library/aa585863\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

