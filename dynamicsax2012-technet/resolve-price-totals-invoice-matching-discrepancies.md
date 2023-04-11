---
title: Resolve price totals invoice matching discrepancies
TOCTitle: Resolve price totals invoice matching discrepancies
ms:assetid: 53f18e61-f50d-4557-b121-5553e79e78b2
ms:mtpsurl: https://technet.microsoft.com/library/Hh292597(v=AX.60)
ms:contentKeyID: 36655928
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Resolve price totals invoice matching discrepancies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this information to identify and resolve matching discrepancies for price totals on invoice lines for purchase orders. You can use the **Pending vendor invoices** list page to identify invoices that have been entered and saved, but that are not yet approved to be posted.


> [!NOTE]
> <P>Use this procedure if the <STRONG>Match price totals</STRONG> field is set to <STRONG>Percentage</STRONG>, <STRONG>Amount</STRONG>, or <STRONG>Percentage and amount</STRONG> in the <STRONG>Accounts payable parameters</STRONG> form.</P>



After you have identified the discrepancy, you might have to contact the vendor if you think that the information on the invoice is incorrect. Depending on the resulting agreement with the vendor, you can do any of the following tasks:

  - Accept the price difference and post the invoice with matching discrepancies.

  - Revise the invoice amount to the expected amount and post the invoice.

  - Request a full credit from the vendor and a new, corrected invoice.

Price totals matching works with matching policies. For more information, see [About Accounts payable invoice matching](about-accounts-payable-invoice-matching.md).

## Resolve price totals variances

A price variance exists if the invoice price total differs from the purchase order price total by an amount that exceeds the allowable price total tolerances that are specified in the **Accounts payable parameters** form. If multiple invoice lines have been posted or saved for the same purchase order line, the price totals for all the invoice lines can be considered when the system evaluates whether a matching discrepancy exists for the invoice line that you are working with. The price variance might be because of different prices per unit, purchase price units, line item discounts, charges that are allocated to the invoice lines, quantities, or a combination of these factors.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Pending vendor invoices**.

2.  Double-click a pending invoice that has a corresponding purchase order. The **Vendor invoice** form opens. For more information, see [Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md).

3.  If a product receipt has not been posted for the purchase order, select **Ordered quantity** in the **Default quantity for lines** field.

4.  On the **Action Pane**, click the **Review** tab, and then click **Matching details**.

5.  Select an invoice line for which a warning icon is displayed.

6.  Review the information in the following fields:
    
      - **Invoice net amount**
    
      - **Expected net amount**
    
      - **Unmatched purchase price total**
    
      - **Unmatched purchase price total percentage**
    
      - **Purchase price total tolerance percent**
    
      - **Unmatched purchase price total in accounting currency**
    
      - **Purchase price total tolerance**

7.  To accept the price difference and post the invoice with matching discrepancies, select the **Approve posting with matching discrepancies** check box, enter a comment, and then click **OK**.
    

    > [!NOTE]
    > <P>If the <STRONG>Post invoice with discrepancies</STRONG> field in the <STRONG>Accounts payable parameters</STRONG> form is set to <STRONG>Allow with warning</STRONG>, these fields are not available and you can skip this step.</P>



8.  To revise the invoice amount to the expected amount, change the amounts in the **Invoice** column to match the amounts in the **Purchase order** column, and then close the form.

9.  In the **Vendor invoice** form, on the **Vendor invoice header** FastTab, clear the **On hold** check box in the **Invoice status details** field group.

10. On the **Action Pane**, click **Post**. In the **Select the posting settings** dialog box, select print settings, and then click **Post**.
    

    > [!NOTE]
    > <P>Alternatively, you can submit the invoice to be posted by using batch processing.</P>



## See also

[Set up Accounts payable invoice matching](set-up-accounts-payable-invoice-matching.md)

[Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md)

[Invoice matching details (form)](https://technet.microsoft.com/library/hh209713\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


