---
title: Revise the sales tax amount on a transaction before posting
TOCTitle: Revise the sales tax amount on a transaction before posting
ms:assetid: 05933dc9-6d90-4139-97e4-802c2802f05f
ms:mtpsurl: https://technet.microsoft.com/library/Aa569715(v=AX.60)
ms:contentKeyID: 36055955
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Revise the sales tax amount on a transaction before posting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can change the calculated sales taxes for a journal line, purchase order line, vendor invoice line, sales order line, customer invoice line, or free text invoice line.

1.  Open the **Temporary sales tax transactions** form. For more information, see [Temporary sales tax transactions (form)](https://technet.microsoft.com/library/aa591455\(v=ax.60\)).

2.  You can make two kinds of revisions:
    
      - On the **Adjustment** tab for a selected sales tax code line, enter a correction of the sales tax amount in the **Actual sales tax amount** field.
        
        This amount appears in the **Total actual sales tax amount** field at the top of the form, or is added to the adjustment amounts of other sale tax code lines.
    
      - If the transaction has several sales tax code lines, you can enter an adjustment amount in the **Total actual sales tax amount** field.
        
        This amount is then distributed among the sales tax code lines that are shown in the **Sales tax transactions** form.
    
      - If the sales tax code line contains a sales tax charge that has to be adjusted, enter an adjusted sales tax amount in the **Actual sales tax amount** field. The corresponding sales tax charge amount is automatically adjusted in the **Actual sales tax charge** field on the **Adjustment** tab.
        
        You can see the original sales tax charge for the sales tax code line in the **Calculated sales tax charge** field. Sales tax charges are set up for sales tax codes in the **Pct. exempt from sales tax** field in the **Values** form. (Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**. Select a sales tax code and click **Values**).

3.  Close the form by following these steps:
    
      - Click **Apply** to save the changes or click **Reset actuals to calculated** to cancel the changes.
    
      - Press ESC to close the form.

## See also

[Temporary sales tax transactions (form)](https://technet.microsoft.com/library/aa591455\(v=ax.60\))

[Resolve sales tax differences between purchase orders and invoices](resolve-sales-tax-differences-between-purchase-orders-and-invoices.md)

  


