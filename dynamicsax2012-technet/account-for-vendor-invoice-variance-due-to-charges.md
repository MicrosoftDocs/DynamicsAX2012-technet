---
title: Account for vendor invoice variance due to charges
TOCTitle: Account for vendor invoice variance due to charges
ms:assetid: dc6d1f4a-14bb-4077-bcc5-102411f7069f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243192(v=AX.60)
ms:contentKeyID: 36655949
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Account for vendor invoice variance due to charges [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If the charges for an invoice differ from the charges for the purchase orders, you can change the charges for the unposted invoice.

Charges are copied to an unposted invoice from the applicable purchase orders when the invoice is created. During this process, the charges on the invoice are automatically connected to the charges on the purchase order. Purchase order charge transactions that are copied to an invoice are not copied to subsequent invoices for the same purchase orders, if **Fixed** is selected in the **Category** field in the **Charges transactions** form. If **Pcs.**, **Percent**, or **Intercompany percent** is selected, the purchase order charge transactions are also copied to subsequent invoices.

You can add charges to the invoice header or the invoice lines by using the **Charges transactions** form. If you add charges to the invoice header, the charges can be allocated to invoice lines. You can also manually connect the charges on the invoice with the corresponding charges on the purchase order. Only connected charges are included in the charges matching process.


> [!NOTE]
> <P>You can view expected and actual values for <STRONG>Customer/Vendor</STRONG> type charges codes in the <STRONG>Compare charges values - Invoice: %1</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh242731(v=ax.60)">Charges totals details/Compare charges values (form)</A>.</P>



When an invoice is posted, the charge transactions from the invoice are posted. The corresponding charge transactions are removed from the purchase order if **Fixed** is selected in the **Category** field in the **Charges transactions** form. If **Pcs.**, **Percent**, or **Intercompany percent** is selected, the purchase order charge transactions are also copied to subsequent invoices.


> [!NOTE]
> <P>If you are working with an invoice for an intercompany purchase order, you cannot change charges on the invoice. The charges for the intercompany purchase order must match the charges for the corresponding intercompany sales order, and any changes to charges for the invoice for the purchase order will cause posting to fail.</P>



## Enter or correct charge transactions for vendor invoices

If the charges on an invoice differ from the expected charges on the corresponding purchase order, you can change the charge transaction for the invoice before you post the invoice. For example, a charge transaction for a handling fee might be 10.00 on the purchase order, but when the invoice arrives, the handling fee could have increased to 20.00. For information about how to enter invoice information, see [Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md).

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click a pending invoice that has a corresponding purchase order. The **Vendor invoice** form opens.

3.  Select which charge transactions to add, change, or delete:
    
      - To add, change, or delete charge transactions for the invoice header or consolidated invoice header, on the **Action Pane**, click the **Financials** tab, and then click **Maintain charges**.
    
      - To add, change, or delete charge transactions for an invoice line, select an invoice line in the **Lines** grid. Then click **Financials** \> **Maintain charges**.
    
      - To add, change, or delete charges for an invoice header that is included on a consolidated invoice, click **Header view** on the **Action Pane**. On the **Purchase orders** FastTab, click **Charges**.

4.  In the **Charges transactions** form, select a charges code.

5.  Enter the amount of the charges as listed on the invoice that you received from the vendor.

6.  If necessary, you can click **Connect** and connect the selected charge transaction for an invoice header or line to the corresponding purchase order header or line. Close the form.

7.  Close the **Charges transactions** form.

8.  In the **Vendor invoice** form, on the **Action Pane**, click the **Review** tab, and then click **Matching details**.

9.  If your legal entity is set up to use charges matching, in the **Invoice matching details** form, click the **Compared charges** **…** button.

10. In the **Compare charges values - Invoice: %1** form, you can compare information about **Customer/Vendor** type charges for the purchase order and invoice. The comparison includes only charges codes that have the **Compare purchase order and invoice values** check box selected in the **Charges code** form. You can also view matching discrepancies.

## Allocate charges for vendor invoices

If a charge transaction was allocated to purchase order lines and the charge amount is different on the invoice, you can complete one of the following tasks:

  - Adjust the charge amounts for each invoice line.

  - Enter a new charge transaction for the difference, and then allocate it to the invoice lines.


> [!NOTE]
> <P>If you are working with an invoice that has been consolidated and you add a charge to the consolidated invoice header (in the <STRONG>Vendor invoice</STRONG> form), allocation affects all invoice lines that are included on the consolidated invoice. If you add a charge to one of the individual invoice headers (on the <STRONG>Purchase orders</STRONG> FastTab), allocation affects only the invoice lines that are associated with the selected invoice header.</P>



For example, assume that a charge for freight was expected to be 20.00 and was allocated equally to four purchase order lines. If the freight charge on the invoice is 30.00, you can enter an additional charge transaction for 10.00 for the invoice header and allocate it to the four invoice lines. The additional charge amount is allocated only to the invoice lines. The purchase order lines are not affected.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click a pending invoice that has a corresponding purchase order. The **Vendor invoice** form opens.

3.  To add charge transactions to the invoice header, on the **Action Pane**, click the **Financials** tab, and then click **Maintain charges**.

4.  In the **Charges transactions** form, enter the amount of the charges from the invoice that you received from the vendor. In this example, enter 10.00, because that is the difference between the purchase order charges and the invoice charges.

5.  Close the **Charges transactions** form.

6.  In the **Vendor invoice** form, on the **Action Pane**, click the **Financials** tab, and then click **Allocate charges**.

7.  Select how to allocate the charges to the lines. For this example, select **Per line** to allocate the charges equally to all four lines on the invoice.

## See also

[Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md)

[Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md)

[Resolve net unit price invoice matching discrepancies](resolve-net-unit-price-invoice-matching-discrepancies.md)

[Allocate charges (form)](https://technet.microsoft.com/en-us/library/hh697725\(v=ax.60\))

[Charges totals details/Compare charges values (form)](https://technet.microsoft.com/en-us/library/hh242731\(v=ax.60\))

[Charges transactions (form)](https://technet.microsoft.com/en-us/library/aa633876\(v=ax.60\))

[Invoice matching details (form)](https://technet.microsoft.com/en-us/library/hh209713\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

