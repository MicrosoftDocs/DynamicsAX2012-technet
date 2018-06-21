---
title: Record the receipt of vendor invoices and match against received quantities
TOCTitle: Record the receipt of vendor invoices and match against received quantities
ms:assetid: 10264492-71c9-41f9-a940-239c0cdc530a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230921(v=AX.60)
ms:contentKeyID: 36655924
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- invoices
- vendors
- invoice
- receipt
- received quantities
- received quantity
---

# Record the receipt of vendor invoices and match against received quantities [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you receive an invoice from a vendor for goods or services on a purchase order, the business processes might require that the goods or services be received before the invoice can be approved for payment.

This procedure assumes that your legal entity uses the following configuration. For more information, see [Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md) and [About Accounts payable invoice matching](about-accounts-payable-invoice-matching.md).

In the **Accounts payable parameters** form:

  - The **Enable invoice matching validation** check box is selected.

  - The **Post invoice with discrepancies** field is set to **Require approval**.

  - The **Display unit price match icon** field is set to **If greater than tolerance**.

  - The **Line matching policy** field is set to **Three-way matching**.

In the **Price tolerances** form:

  - The price tolerance percentage for the legal entity, for **All** items and **All** accounts, is zero percent.

Use the **Vendor invoice** form to enter invoice information. If necessary, you can use the **Invoice matching details** form to view, correct, and approve invoice lines with matching discrepancies for posting.

## Enter and match individual vendor invoices

Use the **Vendor invoice** form to enter invoice information. If necessary, you can use the **Invoice matching details** form to view, correct, and approve invoice lines with matching discrepancies for posting.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  On the **Action Pane**, click **Invoice**. The **Vendor invoice** form opens.

3.  On the **Vendor invoice header** FastTab, select a vendor account, and then enter the invoice number.

4.  Select one or more purchase orders that correspond to the invoice.

5.  At the top of the form, in the **Default quantity for lines** field, select **Product receipt quantity**. The **Lines** grid displays information about purchase order lines for which a product receipt has been posted, but an invoice has not been posted.

6.  On the **Action Pane**, click **Totals**, and then compare the information in the form with the information on the invoice that you received from the vendor. If the amounts differ, note the discrepancies. Close the form.

7.  If the invoice includes a subset of the line items on the purchase order or purchase orders, on the **Action Pane**, click **Match product receipts**. Select the appropriate product receipts and close the form.

8.  In the **Vendor invoice** form, in the **Lines** grid, compare the line item information in the form with the line items on the invoice that you received from the vendor.

9.  If the amounts or quantities on a single invoice line differ from the invoice that you received from the vendor, make the necessary corrections in the fields in the **Lines** grid.

10. If you made changes in step 9 that cause a price variance that exceeds the allowable price variance tolerance, or if the line contains a quantity variance, a warning icon is displayed in the **Match variance** field on the **Vendor invoice header** FastTab.
    
    1.  On the **Action Pane**, click the **Review** tab, and then click **Matching details**. A warning icon is displayed in the **Match variance** column for each invoice line that contains either a price or quantity matching discrepancy.
    
    2.  Select an invoice line for which a warning icon is displayed.
    
    3.  Review the information in the form and make any necessary corrections. For more information, see [Invoice matching details (form)](https://technet.microsoft.com/en-us/library/hh209713\(v=ax.60\)).
    
    4.  Repeat steps b and c for the remaining invoice lines in the form.
    
    5.  If matching discrepancies remain and **Require approval** is selected in the **Post invoice with discrepancies** field in the **Accounts payable parameters** form, you can select the **Approve posting with matching discrepancies** check box to approve the invoice for posting.
    
    6.  If matching discrepancies remain and you must contact the vendor or a coworker to resolve the differences, close the **Invoice matching details** form. In the **Vendor invoice** form, select the **On hold** check box on the **Vendor invoice header** FastTab. For more information, see [Resolve net unit price invoice matching discrepancies](resolve-net-unit-price-invoice-matching-discrepancies.md) and [Resolve price totals invoice matching discrepancies](resolve-price-totals-invoice-matching-discrepancies.md).
    

    > [!NOTE]
    > <P>If the <STRONG>Matching details</STRONG> button is not available, you might not have access to the <STRONG>Invoice matching details</STRONG> form. In the <STRONG>Vendor invoice</STRONG> form, you can select the <STRONG>On hold</STRONG> check box to prevent the invoice from being posted. After another worker verifies the invoice matching information, you can clear the <STRONG>On hold</STRONG> check box and post the invoice.</P>



## Match multiple vendor invoices

You can match vendor invoices to product receipts for multiple invoices at the same time. You might do this if vendor invoices were received through a service or vendor portal and submitted for review through workflow, and you want to perform the invoice matching process immediately instead of waiting for a scheduled task. Only vendor invoices that are submitted to workflow review and are waiting for the **Review vendor invoice matching** task can be matched by using this procedure. Product receipt numbers must be included with the vendor invoices to be matched.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Select one or more invoices.

3.  On the **Action Pane**, click the **Review** tab, and then click **Match product receipts**. The **Infolog** form displays the results of the matching process.

4.  On the **Pending vendor invoices** list page, view the **Last match variance** field.
    
      - **OK** – Match variances are within allowable tolerances.
    
      - **Warning** – Match variances exceed allowable tolerances. Select the invoice, and then click **Matching details** to view the discrepancies.

## See also

[Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\))

[Invoice matching details (form)](https://technet.microsoft.com/en-us/library/hh209713\(v=ax.60\))

[Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md)

[Resolve invoice totals invoice matching discrepancies](resolve-invoice-totals-invoice-matching-discrepancies.md)

[Resolve net unit price invoice matching discrepancies](resolve-net-unit-price-invoice-matching-discrepancies.md)

[Resolve price totals invoice matching discrepancies](resolve-price-totals-invoice-matching-discrepancies.md)

[Account for vendor invoice variance due to charges](account-for-vendor-invoice-variance-due-to-charges.md)

[Correct a vendor invoice that was matched to the wrong product receipt line](correct-a-vendor-invoice-that-was-matched-to-the-wrong-product-receipt-line.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

