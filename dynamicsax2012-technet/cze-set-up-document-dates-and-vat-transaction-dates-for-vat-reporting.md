---
title: (CZE) Set up document dates and VAT transaction dates for VAT reporting
TOCTitle: (CZE) Set up document dates and VAT transaction dates for VAT reporting
ms:assetid: 80948634-12ca-4199-b1df-8ad9ac5ee93f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677586(v=AX.60)
ms:contentKeyID: 49384889
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Set up document dates and VAT transaction dates for VAT reporting 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

For auditing purposes, you must set up the sales date and the document receipt date for value-added tax (VAT) reporting. The sales date is the fulfillment date of the sales order. The document receipt date is the date on which you can claim a deduction for value-added tax (VAT).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Select the sales tax group from the **Sales tax group** list.

2.  On the **General** FastTab, select an option in the **Date of VAT register filling** field.
    
    The option that you select determines how the registration date of the VAT transaction is recorded. For example, you can enter the registration date manually, or use the sales date or the posting date.

3.  In the **Sales date filling** field, select how the sales date is recorded. For example, the sales date can be the same date as the registration of the VAT transaction, or the last date of delivery for the products.

4.  Select the **Mandatory sales date** check box to require that the sales date must be used to validate sales invoices.

## See also

[(CZE) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj677580\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

