---
title: 'Key tasks: Vendor invoices'
TOCTitle: 'Key tasks: Vendor invoices'
ms:assetid: 62f9fc46-4028-4358-99b1-c8a8cf008884
ms:mtpsurl: https://technet.microsoft.com/library/Hh209199(v=AX.60)
ms:contentKeyID: 36057680
author: tonyafehr
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- invoices
- invoice
- vendor invoice
- non-PO invoice
- purchase invoice
- PO invoice
- non-PO invoices
- PO invoices
- purchase invoices
- vendor invoices
- purchase order invoices
- purchase order invoice
- accounts payable invoice
- AP invoice
- accounts payable invoices
- AP invoices
audience: Application User
ms.search.region: Global
---

# Key tasks: Vendor invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A vendor invoice for a purchase order is an invoice that is attached to a purchase order. It contains a header and one or more lines for items or services. A vendor invoice finishes the purchase order, product receipt, and vendor invoice cycle. You can also enter vendor invoices that are not associated with purchase orders.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>(FRA) To create or review mandats and bordereaux de mandat related to a vendor invoice, see <A href="fra-key-tasks-mandats-de-paiement-and-bordereaux-de-mandat-public-sector.md">(FRA) Key tasks: Mandats de paiement and bordereaux de mandat (Public sector)</A>.



## What do you want to do?

Learn more about...

Enter and save vendor invoices for purchase orders

Add invoice lines that are not for a purchase order

Post vendor invoices in the Vendor invoice form

Submit a vendor invoice for review

Enter and match vendor invoices to product receipts

Enter, post, and print multiple invoices as a periodic task

Post and print multiple vendor invoices from the invoice approval journal

New in Microsoft Dynamics AX 2012 R3 Cumulative Update 8 and hotfix KB3047235

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About Accounts payable invoice matching](about-accounts-payable-invoice-matching.md)

[About assets acquired through procurement](about-assets-acquired-through-procurement.md)

[Accounting for stocked items on product receipts and vendor invoices (White paper)](accounting-for-stocked-items-on-product-receipts-and-vendor-invoices-white-paper.md)

## Enter and save vendor invoices for purchase orders

You can save invoices in the **Vendor invoice** form. You might have to do this if you are interrupted when you are entering data, or if you have to verify information about the invoice before you post it. You can also put invoices on hold in the **Vendor invoice** form.


> [!NOTE]
> <P>You cannot post invoices that are on hold.</P>



1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  On the **Action Pane**, click **Invoice** \> **Vendor invoice**. The **Vendor invoice** form opens.

3.  Enter or select an invoice account. This is the vendor account for the vendor that sent the invoice.

4.  Enter the invoice number.

5.  On the **Action Pane**, click **Retrieve purchase orders**. Select the **Include** check box for one or more purchase orders or purchase order lines, and then click **OK**.

6.  At the top of the form, in the **Default quantity for lines** field, select the type of quantity to update.
    
      - **Receive now quantity** – Use for partial shipments. The default value in the **Quantity** field is from the **Receive now** quantity field on the purchase order.
    
      - **Ordered quantity** – Use for complete shipments. The default value in the **Quantity** field is from the **Ordered** quantity field on the purchase order.
    
      - **Registered quantity** – Use if the item requires registration, as specified in the **Item model groups** form. The default value in the **Quantity** field is the physical update quantity that has been registered.
    
      - **Product receipt quantity** – Use if a product receipt has already been received for the order. The default value in the **Quantity** field is from the total quantity of available product receipts.
    
      - **Registered quantity and services** – Use if quantities have been registered in arrival journals for stocked items or items that are not stocked. This option also includes services, regardless of whether they are registered.

7.  In the **Lines** grid, select an invoice line and make changes, as needed. For example, if you ordered 10 items but the invoice is for only 5 items, you might change the value in the **Quantity** field to 5.

8.  Review the information on the **Line details** FastTab and make changes, as needed.

9.  Repeat steps 7 and 8 for the remaining lines on the invoice.

10. If your legal entity uses invoice matching, on the **Vendor invoice header** FastTab, view the **Match variance** field. An exclamation mark indicates that a matching discrepancy exists for one or more types of invoice matching. A check mark indicates that all invoice matching variances are within acceptable tolerances.

11. To save the invoice without posting it, close the form. The invoice status changes from **New** to **Pending**. You can view the invoice on the **Pending vendor invoices** list page.

Back to top

## Add invoice lines that are not for a purchase order

You can create vendor invoices that are not associated with any purchase orders. These vendor invoices can contain a mixture of invoice lines that are for purchase order lines, and invoice lines that are not for purchase order lines. You can also add invoice lines that are not for a purchase order to a vendor invoice that is associated with a purchase order.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  On the **Action Pane**, click **Invoice** \> **Vendor invoice**. The **Vendor invoice** form opens.

3.  Enter or select an invoice account. This is the account for the vendor that sent the invoice.

4.  Enter the invoice number.

5.  In the **Lines** grid, click **Add line** and enter information about the line. If you enter an item number, lines that are not for a purchase order must have a product type of **Item** or **Service**, and must not be stocked. For more information, see [Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\)).

6.  To view or specify additional information about the line, click the **Line details** FastTab and enter the information.

7.  Optional: Repeat steps 5 and 6 for additional lines.

8.  Optional: To view or specify additional information for the invoice header, on the **Action Pane**, click **Header view**.

9.  Optional: To post the invoice, on the **Action Pane**, click **Post**, and then click **Post** in the form that is displayed.

10. To save the invoice without posting, close the form. You can view the invoice on the **Pending vendor invoices** list page.

Back to top

## Post vendor invoices in the Vendor invoice form

You can post a vendor invoice in the **Vendor invoice** form.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Select an invoice. On the **Action Pane**, click **Edit**. Alternatively, you can double-click an invoice to open the **Vendor invoice** form.

3.  In the **Lines** grid and on the **Line details** FastTab, verify that the information for the invoice matches the invoice from the vendor. To make corrections, enter the new amounts or quantities.

4.  On the **Action Pane**, click **Totals** and verify that the information is correct. Close the **Totals** form.

5.  Verify other information in the form and related forms, as needed.

6.  If the invoice was on hold and all problems with the invoice have been corrected, clear the **On hold** check box. You cannot post invoices that are on hold.

7.  On the **Action Pane**, click **Post**, and then click **Post** in the form that is displayed.

Back to top

## Submit a vendor invoice for review

Your organization might use workflow to manage the review process for vendor invoices. If required, a yellow information bar is displayed at the top of the **Vendor invoice** form or the **Pending vendor invoices** list page. Workflow review can be required for the invoice header, the invoice line, or both. The workflow controls apply to the header or the line, depending on where the focus is before you click the control.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Select an invoice. On the **Action Pane**, click **Edit**. Alternatively, you can double-click an invoice to open the **Vendor invoice** form.

3.  Make any necessary changes, and then click **Submit**.

4.  Read the instructions, enter a comment, and then click **Submit**.
    

    > [!NOTE]
    > <P>To cancel the review process, click <STRONG>Actions</STRONG> &gt; <STRONG>Recall</STRONG>.</P>



Back to top

## Enter and match vendor invoices to product receipts

You can enter and save information for vendor invoices, and you can match invoice lines to product receipt lines. You can also match partial quantities for a line, if you have to.

You can create a vendor invoice based on the product receipt line items that have been received to date, even if all the items for a particular purchase order have not yet been received. You might do this, for example, if a vendor sends one invoice per month that covers all of the deliveries that the vendor ships during that month. Each product receipt represents a partial or complete delivery of the items on the purchase order.

When you post the invoice, the **Invoice remainder** quantity for each item is updated with the total of the received quantities from the selected product receipts. If both the **Invoice remainder** quantity and the **Deliver remainder** quantity for all items on the purchase order are zero, the status of the purchase order changes to **Invoiced**. If the **Invoice remainder** quantity is not zero, the status of the purchase order is unchanged and additional invoices can be entered for it.

This procedure assumes that at least one product receipt has been posted for the purchase order. The vendor invoice is based on these product receipts and reflects the quantities from them. The financial information for the invoice is based on the information that is entered when you post the invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**.

2.  On the **Action Pane**, click **Invoice** \> **Vendor invoice**. The **Vendor invoice** form opens.

3.  In the **Default quantity for lines** field, select the type of quantity to update.

4.  Enter or select an invoice account. This is the account for the vendor that sent the invoice.

5.  Enter the invoice number.

6.  On the **Action Pane**, click **Match product receipts**. Alternatively, in the **Lines** grid, click **Invoice line** \> **Match product receipts**.

7.  In the **Match product receipts to invoice** form, select the **Match** check box for the product receipts to match with the invoice line items. Alternatively, you can click **Select all lines** or **Select all product receipts** to match all product receipts to the invoice.

8.  Optional: To match a partial quantity, enter a quantity in the **Product receipt quantity to match** field.

9.  Click **OK** to close the **Match product receipts to invoice** form and return to the **Vendor invoice** form.

10. To save the invoice without posting it, select the **On hold** check box on the **Vendor invoice header** FastTab.
    
    To post the invoice and close the form, on the **Action Pane**, click **Post**, and then click **Post** in the form that is displayed.

11. Close the form.

Back to top

## Enter, post, and print multiple invoices as a periodic task

You can work with multiple invoices at the same time and post them all at the same time. To do this, open the **Vendor invoice** form by clicking the **Maintain vendor invoices** menu item.

1.  Click **Accounts payable** \> **Periodic** \> **Maintain vendor invoices**.

2.  On the **Action Pane**, click **From purchase order** to create invoices based on purchase orders.

3.  In the **Purchase update** form, enter or select a query and then click **OK**. Invoices are created and are displayed in the **Vendor invoice** form.

4.  Optional: You can combine the proposed invoices by invoice account, order, or automatically. On the **Action Pane**, click **Consolidate invoices**, select consolidation options, and then click **Consolidate**.

5.  Edit the invoice information in the grid. For example, you can enter an invoice number for each line in the grid.

6.  Optional: To change invoice lines for an invoice, select the invoice, and then click **Edit** on the **Action Pane**. Make any changes. On the **Action Pane**, in the **Close** group, click **Invoice details** to return to the grid view.

7.  If an invoice needs more work before you post it, select the invoice and then select the **On hold** check box.

8.  When you are satisfied that the invoices are correct, on the **Action Pane**, click **Post**, and then click **Post** in the form that is displayed.

Back to top

## Post and print multiple vendor invoices from the invoice approval journal

This procedure assumes that at least one product receipt has been posted for the purchase order and that an invoice for the purchase order has been posted in an invoice register. The financial information for the invoice is from the invoice that was posted in the register.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice approval journal**.

2.  Create a journal and then click **Lines**.

3.  Click **Find vouchers**. In the **Find vouchers** form, select a voucher in the **List of vouchers** list, and then click **Select**.

4.  Click **OK** to close the **Find vouchers** form.

5.  On the **Overview** tab, enter an account.

6.  Click the **General** tab and verify that the sales tax and currency information is correct.

7.  Click **Functions** \> **Purchase order**.

8.  Optional: Modify the query in the **Query used** form, and then click **OK**. The **Vendor invoice** form is displayed.

9.  In the **Default quantity for lines** field, select **Product receipt quantity**.

10. On the **Action Pane**, click **From product receipt**.

11. In the **Select product receipt** form, select the **Include** check box for the product receipt lines to include on this invoice.

12. Click **OK**. The total invoice amount on the invoice that is calculated based on the product receipt is compared to the total invoice amount on the registered invoice. If they are equal, the vendor invoices are posted and printed. If they are not equal, messages are displayed.

Back to top

## New in Microsoft Dynamics AX 2012 R3 Cumulative Update 8 and hotfix KB3047235

If you are in the public sector, you can now create one or more one-time vendor accounts at the same time as you create invoices for those vendors. For more information, see [Create a one-time vendor and invoice (Public sector)](create-a-one-time-vendor-and-invoice-public-sector.md) and [Import and create one-time vendors and invoices (Public sector)](import-and-create-one-time-vendors-and-invoices-public-sector.md). This feature is available only if AX 2012 R3 CU8 is installed, and if the **Public Sector** configuration key is selected.

If you plan to use general budget reservations with invoices, see [Relieve a general budget reservation (Public sector)](relieve-a-general-budget-reservation-public-sector.md). When a general budget reservation is selected on a vendor invoice line, all project details and project distributions are copied. Because of the budget reservation reference, some of the project details are not editable. Note that in a vendor invoice line detail, you should select a procurement category before selecting a general budget reservation line. If the budget reservation line is selected first, the Procurement category field is disabled.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



Back to top

## Find form help

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

[Purchase posting (form)](https://technet.microsoft.com/library/aa587152\(v=ax.60\))

[Match product receipts to invoice (form)](https://technet.microsoft.com/library/hh209552\(v=ax.60\))

[Select product receipt - Purchase order (form)](https://technet.microsoft.com/library/hh597253\(v=ax.60\))

## Find related tasks

[Create a purchase order](create-a-purchase-order.md)

[Add invoices to invoice groups](add-invoices-to-invoice-groups.md)

[Add invoices to payment groups](add-invoices-to-payment-groups.md)

[Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md)

[Resolve invoice totals invoice matching discrepancies](resolve-invoice-totals-invoice-matching-discrepancies.md)

[Resolve net unit price invoice matching discrepancies](resolve-net-unit-price-invoice-matching-discrepancies.md)

[Resolve price totals invoice matching discrepancies](resolve-price-totals-invoice-matching-discrepancies.md)

[Account for vendor invoice variance due to charges](account-for-vendor-invoice-variance-due-to-charges.md)

[Resolve sales tax differences between purchase orders and invoices](resolve-sales-tax-differences-between-purchase-orders-and-invoices.md)

  


