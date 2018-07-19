---
title: Perform a price query
TOCTitle: Perform a price query
ms:assetid: 117353c9-98ee-48dc-8edb-53e8843100bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271454(v=AX.60)
ms:contentKeyID: 36384086
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPPriceQuery
- EPPriceQueryInfo
audience: Application User
ms.search.region: Global
---

# Perform a price query 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Perform price query** page to enter a query to calculate the item prices for a customer. The item prices are based on price agreements. After you perform a price query, you can create a sales order or sales quotation based on the price query information.

1.  Open the **Perform price query** page by using one of the following methods:
    
      - Click **Sales** on the top link bar, and then click **Customers** on the Quick Launch. The **All customers** page is displayed. Select the customer to perform the query for and on the **Action Pane**, on the **Customer** tab, in the **Price** group. click **Perform price query**.
        
        \-or-
    
      - Click **Sales** on the top link bar, and then click **Quotations** on the Quick Launch. The **All quotations** page is displayed. On the **Action Pane**, on the **Quotation** tab, in the **Common actions** group, click **Perform price query**.
        
        \-or-
    
      - Click **Sales** on the top link bar, and then click **Sales orders** on the Quick Launch. The **All sales orders** page is displayed. On the **Action Pane**, on the **Sell** tab, in the **Perform** group, click **Perform price query**.

2.  If you opened the **Perform price query** page from the **All quotations** page or the **All sales orders** page, enter or select the customer to perform the query for and then click **Next**.

3.  Click **Add line** to add an item to the query.

4.  Select an item from the list of items and enter the sales quantity to calculate the price for. Also select any inventory dimensions, if it is required.

5.  Repeat steps 3 and 4 to add more items to the query.

6.  Click **Next** to add all the selected items to the query and to start the calculation of the price.

7.  Select whether to create a sales quotation or a sales order from the price query.

8.  Click **Finish**. One of the following pages is displayed:
    
    1.  If you selected **Sales order**, the **New sales order** page is displayed. On this page, you can create a sales order for the items in the query. Click **Save and close** to create the new sales order. For more information, see [Create or edit a sales order](create-or-edit-a-sales-order.md).
    
    2.  If you selected **Quotation**, the **New sales quotation** page is displayed. Click **Save and close** to create the new sales quotation.
    
    3.  If you selected **None**, the prices are calculated and no additional action is taken.

## See also

[View customer price agreements](view-customer-price-agreements.md)

  


