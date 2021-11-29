---
title: (IND) Invoice an export sales order
TOCTitle: (IND) Invoice an export sales order
ms:assetid: e5ff7862-3c4a-4c09-8f4b-caf7687cf7a3
ms:mtpsurl: https://technet.microsoft.com/library/JJ710889(v=AX.60)
ms:contentKeyID: 49386302
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Invoice an export sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can update the financial entries for the items and the customer account when the **Export order** check box is selected for the sales order that is invoiced. The financial entries for the customs duty are updated when the shipping bill is posted for either a partial quantity of the sales order or the full quantity. When the shipping bill is posted, a new order line is created in the corresponding export order in the **Export order** form.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. Select the sales order that is ready for invoicing. Alternatively, on the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customs export order**. On the **Action Pane**, in the **New** group, click **Export order**.
    
    If you create a new sales order, select the **Export order** check box when you create the order.

2.  On the **Action Pane**, on the **Sell** tab, in the **Generate** group, click **Confirmation**.
    
    –or–
    
    On the **Action Pane**, on the **Pick and pack** tab, in the **Generate** group, click **Picking list**.
    
    –or–
    
    On the **Action Pane**, on the **Pick and pack** tab, in the **Generate** group, click **Packing slip**.
    
    –or–
    
    On the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

3.  Click the **Other** tab.

4.  In the **Order** field, verify that the **Export order** check box is selected.

5.  In the lower pane, on the **Lines** tab, view the information in the **Assessable value** and **Net amount** fields.

6.  Click **OK**.

## See also

[(IND) Post receipt lists, product receipts and purchase order invoices](ind-post-receipt-lists-product-receipts-and-purchase-order-invoices.md)

[(IND) Sales orders (modified form)](https://technet.microsoft.com/library/jj677998\(v=ax.60\))

  


