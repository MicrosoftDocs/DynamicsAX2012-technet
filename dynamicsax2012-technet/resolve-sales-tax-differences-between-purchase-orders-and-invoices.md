---
title: Resolve sales tax differences between purchase orders and invoices
TOCTitle: Resolve sales tax differences between purchase orders and invoices
ms:assetid: 8a9bc094-482e-493d-addd-74418aa12693
ms:mtpsurl: https://technet.microsoft.com/library/Hh292600(v=AX.60)
ms:contentKeyID: 36655938
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Resolve sales tax differences between purchase orders and invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Sometimes, the sales tax for a purchase order and the sales tax for the corresponding vendor invoice differ. When this occurs, you should verify that the sales tax codes and sales tax amounts are correct for the vendor invoice.


> [!NOTE]
> <P>If changes are needed, make corrections to the invoice lines before you change the sales tax information in the <STRONG>Sales tax transactions</STRONG> form. This includes changes that might affect the sales tax calculations. These changes include unit prices, quantities, and so on. It is especially important that you make any necessary changes to tax groups for invoice lines first. If you change tax groups for invoice lines, previous changes that you have made in the <STRONG>Sales tax transactions</STRONG> form might be recalculated.</P>



## Purchase order and vendor invoice sales tax total amounts differ

The sales tax total amounts for the purchase order and for the vendor invoice that you receive from the vendor might differ. If invoice totals invoice matching is enabled, these differences could cause a matching discrepancy. If the **Post invoice with discrepancies** field in the **Accounts payable parameters** form is set to **Require approval**, and you are authorized to do this, you can approve the matching variance. If necessary, you can change a tax group for the invoice or correct the tax amounts for the invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click an invoice. The **Vendor invoice** form opens.

3.  On the **Action Pane**, on the **Financials** tab, click **Sales tax**.

4.  Compare the sales tax codes in the **Sales tax transactions** form with the sales tax codes on the invoice that you received from the vendor. If the invoice from the vendor includes sales tax codes that differ from the sales tax codes for the purchase order, determine whether the purchase order or the invoice is correct.
    
      - If the purchase order is correct, you can put the invoice on hold until the vendor provides a new invoice, and then continue to step 6. For information about putting an invoice on hold, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).
    
      - If the invoice from the vendor is correct, follow these steps:
        
        1.  Close the **Sales tax transactions** form.
        
        2.  In the **Vendor invoice** form, select different tax groups for one or more invoice lines.
        
        3.  On the **Action Pane**, on the **Financials** tab, click **Sales tax**.

5.  Compare the sales tax amounts in the **Sales tax transactions** form with the sales tax amounts on the invoice that you received from your vendor. If the invoice from the vendor includes sales tax amounts that differ from the sales tax amounts for the purchase order, determine whether the purchase order or the invoice is correct.
    
      - If the purchase order is correct, you can put the invoice on hold until the vendor provides a new invoice, and then continue to step 6. For information about putting an invoice on hold, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).
    
      - If the invoice from the vendor is correct, follow these steps:
        
        1.  On the **Adjustment** tab, in the **Total calculated sales tax amount** field, enter the correct sales tax amount.
        
        2.  Select the **Override calculated sales tax** check box.
        
        3.  Optional: The calculated sales tax amount might be incorrect if the tax rate for the sales tax code is incorrect. Verify the tax rate in the **Sales tax codes** form. (Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.)

6.  Close the **Sales tax transactions** form.

7.  If required, verify invoice matching information. In the **Vendor invoice** form, view the **Match variance** field.
    
      - If a check mark is displayed, any matching discrepancies that might exist for the invoice are within acceptable tolerances. Unless the invoice has other problems, it can be posted.
    
      - If an exclamation mark is displayed, matching discrepancies exceed the acceptable tolerances. Complete the following steps:
        
        1.  On the **Action Pane**, on the **Review** tab, click **Matching details**.
        
        2.  Compare the information in the **Invoice matching details** form with the invoice that you received from the vendor. If an exclamation icon is displayed next to the **Invoice amount** field, the difference between the total invoice amount on the vendor invoice and the expected total invoice amount exceeds the tolerance that is specified for invoice totals matching. Discrepancies between sales tax totals are included in invoice totals matching.
        
        3.  If you are authorized to do this, you can click **Approve posting with matching discrepancies** to allow the invoice to be posted.
        
        4.  Close the form.

8.  In the **Vendor invoice** form, save or post the invoice.

## Purchase order and vendor invoice sales tax codes differ

The sales tax codes for the purchase order and the vendor invoice might differ. You can change a tax group for the invoice, delete any sales tax codes that are not derived from the tax groups for the invoice, or reset the actual sales tax amount to the calculated amount.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click an invoice. The **Vendor invoice** form opens.

3.  On the **Action Pane**, on the **Financials** tab, click **Sales tax**.

4.  Compare the sales tax codes in the **Sales tax transactions** form with the sales tax information for the invoice that you received from the vendor. If the invoice from the vendor includes sales tax codes that differ from the sales tax codes for the purchase order, determine whether the purchase order or the invoice is correct.
    
      - If the purchase order is correct, you can put the invoice on hold until the vendor provides a new invoice, and then continue to step 5. For information about putting an invoice on hold, see [Key tasks: Vendor invoices](key-tasks-vendor-invoices.md).
    
      - If the invoice from the vendor is correct, complete one or more of the following procedures.
        
        ### Change tax groups for the invoice
        
        1.  Close the **Sales tax transactions** form.
        
        2.  In the **Vendor invoice** form, select different tax groups for one or more invoice lines.
        
        3.  On the **Action Pane**, on the **Financials** tab, click **Sales tax**.
        
        ### Delete non-derived sales tax codes
        
          - In the **Sales tax transactions** form, delete any sales tax code lines that are not included in the tax groups for the invoice lines. This might occur, for example, if the invoice was created by a service. If the **Keep sales tax adjustments for PO invoices** check box is selected in the **Accounts payable parameters** form, transactions that include sales tax code lines that are not derived from the intersection of the tax groups cannot be posted. This means that sales tax code lines that are not included in both the sales tax group and the item tax group for the invoice line cannot be posted.
        
        ### Reset actual amounts to the calculated amounts
        
        1.  In the **Sales tax transactions** form, click the **Adjustment** tab, and then click **Reset actuals to calculated**.
        
        2.  Review the sales tax code lines. If necessary, change the amount in the **Actual sales tax amount** field, and then select the **Override calculated sales tax** check box.

5.  Close the **Sales tax transactions** form.

6.  If required, verify invoice matching information.

7.  In the **Vendor invoice** form, save or post the invoice.

## See also

[Revise the sales tax amount on a transaction before posting](revise-the-sales-tax-amount-on-a-transaction-before-posting.md)

[Invoice matching details (form)](https://technet.microsoft.com/library/hh209713\(v=ax.60\))

[Temporary sales tax transactions (form)](https://technet.microsoft.com/library/aa591455\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


