---
title: Prepare a credit note
TOCTitle: Prepare a credit note
ms:assetid: 8508b8d6-4273-4879-81ce-e67b0cd07961
ms:mtpsurl: https://technet.microsoft.com/library/Hh271586(v=AX.60)
ms:contentKeyID: 36384217
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPSalesCreditNote
audience: Application User
ms.search.region: Global
---

# Prepare a credit note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You use the **Create credit note** page to prepare a credit note for a customer when the customer returns items that have been ordered and received. A credit note is an invoice with a negative amount.


> [!NOTE]
> <P>In the Enterprise Portal, you prepare the credit note by creating one or more negative order lines. You use negative order lines to credit the actual invoice. The procedure is carried out in the Microsoft Dynamics AX client.</P>



1.  Click **Sales** on the top link bar, and then click **Sales orders** on the Quick Launch. The **All sales orders** list page is displayed.

2.  Select the invoiced sales order to prepare a credit note for. On the **Action Pane**, on the **Sell** tab, in the **Credit note** group, click **Credit note**. The **Create credit note** page is displayed.
    

    > [!NOTE]
    > <P>For each sales order in the list page, you can see the status in the <STRONG>Status</STRONG> field.</P>



3.  In the **Lines** FastTab, select the check box for the invoiced item that you want to prepare the credit note for. You can modify the site, warehouse, and sales quantity, if it is required. You can select one or more lines. To select all available lines, click the first check box in the **Lines** FastTab.
    

    > [!NOTE]
    > <P>Although you can prepare multiple credit notes for a sales order, the total quantity of returned or credited items cannot exceed the sales quantity of the invoiced items.</P>
    > <P>When you prepare the credit note, you generate negative order lines for the selected sales order.</P>



4.  On the **Action Pane**, on the **Edit** tab, in the **Commit** group. click **Create** to prepare the credit note. The **View sales order confirmation** page is displayed. This page shows the negative order lines that you have just created for the sales order.

5.  Click **Close** to return to the **All sales orders** list page.
    
    You can view the new credit note lines when you view the sales order information. For more information, see [View sales orders and totals](view-sales-orders-and-totals.md).

## See also

[Create or edit a sales order](create-or-edit-a-sales-order.md)

[View open sales order lines and backorder lines](view-open-sales-order-lines-and-backorder-lines.md)

[Create or edit a return order](create-or-edit-a-return-order.md)

[View return orders](view-return-orders.md)

[View customer invoice information](view-customer-invoice-information.md)

  


