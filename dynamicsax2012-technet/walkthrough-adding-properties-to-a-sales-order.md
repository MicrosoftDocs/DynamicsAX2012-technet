---
title: 'Walkthrough: Adding Properties to a Sales Order'
TOCTitle: 'Walkthrough: Adding Properties to a Sales Order'
ms:assetid: 4530651e-1fe0-4288-8c27-6b8808ffff3b
ms:mtpsurl: https://technet.microsoft.com/library/JJ991925(v=AX.60)
ms:contentKeyID: 51595728
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Walkthrough: Adding Properties to a Sales Order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can customize sales order properties to send additional data from your online store to Microsoft Dynamics AX to meet the needs of your business processes.

The starter store has sales order properties that you can use to capture data during order transactions. You can extend the sales order properties to send additional data from your online store to Microsoft Dynamics AX during order transactions. For example, you could add an attribute called GiftWrap to indicate that an item should be wrapped.

To customize sales order properties:

1.  Create an attribute.

2.  Add the attribute to an attribute group.

3.  Assign the attribute group to your online store.

4.  Set the attribute on a sales order.

## Creating an Attribute

To create an attribute, you must define an attribute type and then assign the attribute type to your new attribute. In this example, you use an attribute type that is included in Microsoft Dynamics AX. For more information about attributes, see [Set up attributes and attribute types](set-up-attributes-and-attribute-types.md).

### To create an attribute

1.  In Microsoft Dynamics AX, click **Product information management** \> **Setup** \> **Attributes** \> **Attributes**.

2.  Click **New**. Enter the following values:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>GiftWrap</p></td>
    </tr>
    <tr class="even">
    <td><p>Friendly name</p></td>
    <td><p>Gift wrap</p></td>
    </tr>
    <tr class="odd">
    <td><p>Attribute type</p></td>
    <td><p>StringDomain</p></td>
    </tr>
    </tbody>
    </table>


## Adding the Attribute to an Attribute Group

After you define your attribute, you can add it to an attribute group. For more information about attribute groups, see [Set up retail attribute groups](set-up-retail-attribute-groups.md).

### To create an attribute group and add your attribute

1.  Click **Product information management** \> **Setup** \> **Attributes** \> **Attribute groups**.

2.  Click **New**. Enter the following values:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>SPSalesOrderGroup</p></td>
    </tr>
    <tr class="even">
    <td><p>Friendly name</p></td>
    <td><p>Sales order attribute group</p></td>
    </tr>
    <tr class="odd">
    <td><p>Description</p></td>
    <td><p>Sales order attribute group</p></td>
    </tr>
    </tbody>
    </table>


3.  In **Attributes**, click **Add**.

4.  Select GiftWrap, and then click **Select**.

5.  Click **OK**.

## Assigning the attribute group to your online store

After you create your attribute group, assign it to your online store. For more information, see [Set up an online store](set-up-an-online-store.md).

### To assign an attribute group to your online store

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click your store.

2.  Click the **Set up** tab and then click **Sales order attributes**.

3.  In **Channel attribute groups**, click **New**.

4.  In **Name**, select **SPSalesOrderGroup**.

## Setting the attribute on a sales order

You can add the attribute to a sales order by adding business logic in the commerce runtime. Add the following code to add the attribute to the cart, save the cart, and then create a sales order from the cart.

``` 
            Var cart = orderManager.GetCart(cartId, accountNumber, false);
            cart.AttributeValues.Add(new AttributeTextValue { Name = "GiftWrap", TextValue = "Yes" });
            orderManager.SaveCart(cart);
            orderManager.CreateOrderFromCart(…);
```

## Next Steps

After you create a sales order on the commerce runtime, you can view the new attribute in Microsoft Dynamics AX.

### To view the attribute in Microsoft Dynamics AX

1.  In Microsoft Dynamics AX, click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**. Run the job **P-0001\_OC** to run POS transactions in the online channel.

2.  Click **Retail** \> **Periodic** \> **Synchronize online orders** to create a sales order in Microsoft Dynamics AX.

3.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Click the **Retail** tab, and then click **Retail attributes**. You should see the attribute you created.

  


