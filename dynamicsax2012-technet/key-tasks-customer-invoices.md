---
title: 'Key tasks: Customer invoices'
TOCTitle: 'Key tasks: Customer invoices'
ms:assetid: 284a30a9-ca94-4beb-b661-c4f13ab3a278
ms:mtpsurl: https://technet.microsoft.com/library/Hh208491(v=AX.60)
ms:contentKeyID: 36056215
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- accounts receivable
- bill
- billing
- bills
- customer invoice
- customer invoices
- sales invoice
- sales invoices
- sales order invoice
- sales order invoices
audience: Application User
ms.search.region: Global
---

# Key tasks: Customer invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A customer invoice for a sales order is an invoice that is attached to a sales order. It contains a header and one or more lines for items or services. The customer invoice finishes the sales order, packing slip, and sales invoice cycle.

## What do you want to do?

Learn more about...

Post and print individual customer invoices based on sales orders

Post and print individual customer invoices based on packing slips and date

Post and print multiple customer invoices based on packing slips and date

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About customer invoices, free text invoices, and pro forma invoices](about-customer-invoices-free-text-invoices-and-pro-forma-invoices.md)

## Post and print individual customer invoices based on sales orders

Use this procedure to create an invoice that is based on a sales order. You might do this if you decide to invoice the customer before delivering the goods or services.

When you post the invoice, the **Invoice remainder** quantity for each item is updated with the total of the invoiced quantities from the selected sales order. If both the **Invoice remainder** quantity and the **Deliver remainder** quantity for all items on the sales order are zero, the status of the sales order changes to **Invoiced**. If the **Invoice remainder** quantity is not zero, the status of the sales order is unchanged and additional invoices can be entered for it.

Inventory transactions are updated with the invoice number, and the status in the sales order **Line status** field changes to **Invoiced**.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select one or more sales orders.

3.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** in the **Generate** group.

4.  In the **Quantity** field, select **All**.

5.  Select the **Posting** check box.

6.  Make selections in the **Print options** field group as needed.

7.  Optional: Verify totals, tax, and quantities.
    
    1.  To view totals for a sales invoice, select an invoice, click **Totals**, view the information, and then close the form.
    
    2.  To view sales taxes for a customer invoice, select an invoice, click **Sales tax**, view the information, and then close the form.
    
    3.  To view or change quantities for a line item, click the **Lines** tab and select a line. The **Update** field contains the quantity for the line item that has not been invoiced yet.

8.  Optional: Repeat step 7 for additional sales orders.

9.  Click **OK**. The customer invoices are posted and printed.

10. On the **All sales orders** list page, you can view the status of the sales orders in the grid.

11. Optional: Use the **Open customer invoices** list page to view the invoices that you posted. (Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Open customer invoices**.)

Back to top

## Post and print individual customer invoices based on packing slips and date

This procedure assumes that at least one packing slip has been posted for the sales order. The customer invoice is based on these packing slips and reflects the quantities from them. The financial information for the invoice is based on the information that is entered when you post the invoice.

You can create a customer invoice based on the packing slip line items that have been shipped to date, even if all the items for a particular sales order have not yet been shipped. You might do this, for example, if your legal entity issues one invoice per customer per month that covers all of the deliveries that you ship during that month. Each packing slip represents a partial or complete delivery of the items on the sales order.

When you post the invoice, the **Invoice remainder** quantity for each item is updated with the total of the delivered quantities from the selected packing slips. If both the **Invoice remainder** quantity and the **Deliver remainder** quantity for all items on the sales order are zero, the status of the sales order changes to **Invoiced**. If the **Invoice remainder** quantity is not zero, the status of the sales order is unchanged and additional invoices can be entered for it.

Inventory transactions are updated with the invoice number, and the status in the sales order **Line status** field changes to **Invoiced**.

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select one or more sales orders that have had packing slips posted for them.

3.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** in the **Generate** group.

4.  In the **Quantity** field, select **Packing slip**.

5.  Select the **Posting** check box.

6.  Make selections in the **Print options** field group as needed.

7.  On the **Overview** tab in the lower pane, select an invoice line and view the **Packing slip** field. If **\<multiple\>** is shown, multiple packing slips have been posted for this sales order.

8.  Click **Select packing slip**.

9.  In the **Select packing slip** form, review the list of packing slips on the **Overview** tab in the upper pane. By default, all posted packing slips for the sales orders are included on the invoice. If the invoice should not include some packing slips, clear the **Include** check box for those packing slips.

10. Click **OK** to close the form.

11. Optional: Repeat steps 7 through 10 for additional sales orders.

12. Click **OK**. The customer invoices are posted and printed.

13. On the **All sales orders** list page, you can view the status of the sales orders in the grid.

14. Optional: Use the **Open customer invoices** list page to view the invoices that you posted. (Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Open customer invoices**.)

Back to top

## Post and print multiple customer invoices based on packing slips and date

This procedure assumes that at least one packing slip has been posted for the sales orders that are invoiced using the periodic job. The financial information for the invoices is based on the information that is entered when you enter and post the invoices.

1.  Click **Accounts receivable** \> **Periodic** \> **Sales update** \> **Invoice**.

2.  In the **Quantity** field, select **Packing slip**.

3.  Optional: Click **Select** and modify the query in the **Sales update** form. For example, you might select a range of dates for the **Ship date** field. Click **OK** to close the form.

4.  Select the **Posting** check box.

5.  Make selections in the **Print options** field group as needed.

6.  On the **Other** tab, in the **Summary update for** field, select **None**.

7.  Click **Select packing slip**.

8.  In the **Select packing slip** form, review the list of packing slips on the **Overview** tab in the upper pane. By default, all posted packing slips for the sales orders are included on the invoices. If the invoices should not include some packing slips, clear the **Include** check box for those packing slips.

9.  Click **OK** to close the form.

10. In the **Posting invoice** form, click the **Lines** tab. The packing slip number and ship date are displayed on this tab. They are also printed on the invoice if you print invoice documents.

11. Click **OK**. The customer invoices are posted and printed.

12. On the **All sales orders** list page, you can view the status of the sales orders in the grid.

13. Optional: Use the **Open customer invoices** list page to view the invoices that you posted. (Click **Accounts receivable** \> **Common** \> **Customer invoices** \> **Open customer invoices**.)

Back to top

## Find form help

[Sales posting (form)](https://technet.microsoft.com/library/aa550287\(v=ax.60\))

[Select sales order packing slip (form)](https://technet.microsoft.com/library/hh580614\(v=ax.60\))

## Find related tasks

[Summarize customer invoices based on packing slip numbers](summarize-customer-invoices-based-on-packing-slip-numbers.md)

  


