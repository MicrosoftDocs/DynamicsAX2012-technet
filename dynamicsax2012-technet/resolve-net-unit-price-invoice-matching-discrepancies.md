---
title: Resolve net unit price invoice matching discrepancies
TOCTitle: Resolve net unit price invoice matching discrepancies
ms:assetid: 82852252-b348-436b-92fb-f26f3982337c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213157(v=AX.60)
ms:contentKeyID: 36655937
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Resolve net unit price invoice matching discrepancies [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this information to identify and resolve common types of price variances and quantity variances, which are collectively known as matching discrepancies. You can use the **Pending vendor invoices** list page to identify invoices that have been entered and saved, but that are not yet approved to be posted.

After you have identified the discrepancy, you might have to contact the vendor if you think that the information on the invoice is incorrect. Depending on the resulting agreement with the vendor, you can do any of the following tasks:

  - Accept the price difference and post the invoice with matching discrepancies.

  - Revise the invoice amount to the expected amount and post the invoice.

  - Request a full credit from the vendor and a new, corrected invoice.

Net unit price matching works with matching policies such as two-way matching or three-way matching. For more information, see [About Accounts payable invoice matching](about-accounts-payable-invoice-matching.md).

## Resolve net unit price variances

A price variance exists if the invoice net unit price differs from the purchase order net unit price by an amount that exceeds the allowable price tolerance. The price variance might be because of different prices per unit, purchase price units, line item discounts, charges that are allocated to the invoice lines, quantities, or a combination of these factors.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click a vendor invoice that has a corresponding purchase order. The **Vendor invoice** form opens.

3.  On the **Action Pane**, click the **Review** tab, and then click **Matching details**.

4.  Select an invoice line for which a warning icon is displayed.

5.  Review the information in the **Price** field group.

6.  To accept the price difference and post the invoice with matching discrepancies, select the **Approve posting with matching discrepancies** check box, enter a comment, and then click **OK**.
    

    > [!NOTE]
    > <P>If the <STRONG>Post invoice with discrepancies</STRONG> field in the <STRONG>Accounts payable parameters</STRONG> form is set to <STRONG>Allow with warning</STRONG>, these fields are not available and you can skip this step.</P>



7.  To revise the invoice amount to the expected amount, change the amounts in the **Invoice** column to match the amounts in the **Purchase order** column, and then close the form.

8.  In the **Vendor invoice** form, on the **Vendor invoice header** FastTab, clear the **On hold** check box in the **Invoice status details** field group.

9.  On the **Action Pane**, click **Post**. In the **Select the posting settings** dialog box, select print settings, and then click **Post**.
    

    > [!NOTE]
    > <P>Alternatively, you can submit the invoice to be posted by using batch processing.</P>



## Resolve quantity variances

If the **Receiving requirements** check box is selected for the inventory model group for an item, a product receipt must be posted before an invoice can be posted for the corresponding line item. Also, the value in the **Quantity** field on the product receipt line must equal the value in the **Quantity** field on the invoice line.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click a vendor invoice that has a corresponding purchase order. The **Vendor invoice** form opens.

3.  On the **Action Pane**, click the **Review** tab, and then click **Matching details**.

4.  Select an invoice line for which a warning icon is displayed.

5.  Review the information in the **Quantity** field group.

6.  To accept the quantity difference and post the invoice with matching discrepancies, select the **Approve posting with matching discrepancies** check box, enter a comment, and then close the form.
    

    > [!NOTE]
    > <P>If the <STRONG>Receiving requirements</STRONG> check box is selected for the item's inventory model group, but the product receipt quantity is less than the invoice quantity, the invoice cannot be posted even if it is approved.</P>



7.  To revise the product receipt quantity to match the invoice quantity, click the **Total product receipts matched** **…** button. In the **Match product receipts to invoice** form, select a different product receipt that has the correct quantity for the invoice line, and then close the form. Close the **Invoice matching details** form.

8.  To revise the invoice quantity to match the product receipt quantity, note the quantity in the **Total product receipts matched** field, and then close the **Invoice matching details** form. In the **Vendor invoice** form, on the **Action Pane**, click the **Vendor invoice** tab. In the **Lines** grid, select an invoice line and change the quantity in the **Quantity** field.

9.  On the **Vendor invoice header** FastTab, clear the **On hold** check box in the **Invoice status details** field group.

10. On the **Action Pane**, click **Post**. In the **Select the posting settings** dialog box, select print settings, and then click **Post**.
    

    > [!NOTE]
    > <P>Alternatively, you can submit the invoice to be posted by using batch processing.</P>



## See also

[Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md)

[Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md)

[Invoice matching details (form)](https://technet.microsoft.com/en-us/library/hh209713\(v=ax.60\))

[Match product receipts to invoice (form)](https://technet.microsoft.com/en-us/library/hh209552\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

