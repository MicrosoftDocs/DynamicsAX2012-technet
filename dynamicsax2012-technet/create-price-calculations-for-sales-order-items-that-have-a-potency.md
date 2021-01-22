---
title: Create price calculations for sales order items that have a potency
TOCTitle: Create price calculations for sales order items that have a potency
ms:assetid: 0367775b-9115-435b-935b-0077c1a3ac5e
ms:mtpsurl: https://technet.microsoft.com/library/Dn527688(v=AX.60)
ms:contentKeyID: 59626221
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create price calculations for sales order items that have a potency 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the information in this topic to create and validate price calculations for sales order items that have a potency and to process the sales order for the items. The concentration of an active ingredient in an item is defined as the item’s potency. Before you can create sales orders for items with potency, you must complete the following tasks.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up an attribute-based pricing formula.</p></td>
<td><p><a href="set-up-an-attribute-based-pricing-formula-for-a-sales-item-that-uses-potency.md">Set up an attribute-based pricing formula for a sales item that uses potency</a></p></td>
</tr>
<tr class="even">
<td><p>Create a batch attribute of the type <strong>Integer</strong> or <strong>Fraction</strong> for the potency item.</p></td>
<td><p><a href="create-a-batch-attribute.md">Create a batch attribute</a></p></td>
</tr>
</tbody>
</table>


## Create a product that uses potency

Create a released product that will be the starting point for inventory items that you can include on a sales order.

To create a product that uses potency, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  On the **Action Pane** in the **New** group, click **Product** to create a new product and enter the following details:
    
      - **Product number** – Create a product number to identify the product. The information is copied to the remaining fields in the **Identification** and **Company-specific identification** groups.
    
      - **Item model group** - Select an item model group.
    
      - **Storage dimension group** – Select a storage dimension group.
    
      - **Tracking dimension group** - Select a tracking dimension group that has the **Active** check box selected for **Batch number**.
    
    For more information about how to create a product, see [Key tasks: Define products](key-tasks-define-products.md).

3.  In the **Released products** form, select the product. On the **Action Pane**, in the **Maintain** group, click **Edit**.

4.  On the **Action Pane**, click **Manage inventory**. In the **Order settings** group, enter the following details:
    
      - Select **Default order settings**. In the **Purchase site**, **Inventory site**, and **Sales site** fields, select the appropriate options.
    
      - Click **Site specific order settings**. On the **Overview** tab, in the **Site**, **Purchase warehouse**, **Inventory warehouse**, and **Sales warehouse** fields, select the appropriate options.

5.  In the **Batch attributes** group, select **Product specific**.

6.  In the **Product specific** form, click **New** to create a new product-specific batch attribute. In the **Attribute relation** field, select either **Integer** or **Fraction**. The values in the **Tolerance action**, **Minimum**, **Maximum**, and **Target** fields are inherited from the attribute that you selected in the **Attribute relation** field.

7.  Click the **Manage inventory** FastTab. In the **Base attribute** field, in the **Potency** field group, select a base attribute. The target value in the **Target** field is derived from the target value of the product-specific batch attribute.

8.  Select a value in the **Record the attribute value** field.

## Add costs for potency items

Define the costs for the product that you want to include in the calculation of the sales price for the potency items.

To add costs for potency items, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select a product that uses potency. On the **Manage costs** **Action Pane** in the **Set up** group, click **Item price**.

3.  On the **Pending prices** tab, in the **Price type** field, select **Cost**.

4.  In the **Version** field, select a costing version setup.

5.  In the **Site** field, select a site and, in the **Price** field, enter a price.

6.  Press **Ctrl**+**S** to save the record, and then click **Activate** to enable the price.

## Add inventory for potency items

Add inventory to associate the product with items on inventory.

To add inventory for potency items, follow these steps:

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Inventory adjustment**.

2.  Click **New** to create a new journal and select a journal name. For more information about inventory journals, see [Using inventory journals](using-inventory-journals.md).

3.  Click **Lines**. In the **Journal lines, inventory** form, select a potency item in the **Item number** field, enter a batch number in the **Batch number** field, and then enter a quantity in the **Quantity** field.

4.  Click **Inventory** and then click **Registration**.

5.  In the **Registration** form, under **Transactions**, select the **Auto-create** check box for the line that is created.

6.  Under **Register now**, enter a value in the **Actual value** field.

7.  Click **Post all**, and close the form.

## Create a sales agreement and add an attribute-based pricing ID

The attribute-based pricing ID associates the sales item with a pricing formula that uses the concentration of an active ingredient in the price calculation.

To create a sales agreement and add an attribute-based pricing ID, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the product that you want to associate with the attribute-based pricing.

3.  On the **Action Pane**, click **Sell**. In the **Trade agreements** group, click **Create trade agreements**.

4.  In the **Price/discount agreement journals** form, in the **Name** field, select a journal name, and then click **Lines**.

5.  In the **Journal lines, price/discount agreement** form, leave the existing values in the following fields:
    
      - **Relation** - **Price (purch.)**
    
      - **Account code** - **All**
    
      - **Item code** - **Table**

6.  In the **Item relation** field, select the product that you want to associate with the attribute-based pricing.

7.  In the **Attribute-based pricing ID** field, select the pricing ID that contains a formula for price calculations.

8.  In the **Amount in currency** field, enter an amount, and then select a currency in the **Currency** field.

## Create and invoice a sales order with a potency item

When you create a sales order for items with potency, the potency of the items is considered in the sales price.

To create and invoice a sales order with a potency item, follow these steps:

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  On the **Action Pane**, in the **New** group, click **Sales order**.

3.  In the **Item number** field, select the potency item, and then complete the sales order.
    
    For more information about sales orders, see [Process sales orders overview](process-sales-orders-overview.md).

4.  Process the invoice for the sales order. The line amount of the potency item is updated when you post the invoice.
    
    For more information about how to create and post an invoice for a sales order, see [Create customer invoices for sales orders](create-customer-invoices-for-sales-orders.md).

## See also

[About potency management](about-potency-management.md)

  


