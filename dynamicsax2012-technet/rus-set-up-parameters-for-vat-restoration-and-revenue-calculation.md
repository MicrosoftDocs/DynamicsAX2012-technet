---
title: (RUS) Set up parameters for VAT restoration and revenue calculation
TOCTitle: (RUS) Set up parameters for VAT restoration and revenue calculation
ms:assetid: a7239720-96f9-45a0-905c-9c1e4224460b
ms:mtpsurl: https://technet.microsoft.com/library/JJ678574(v=AX.60)
ms:contentKeyID: 49387801
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters for VAT restoration and revenue calculation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up parameters for the restoration of value-added tax (VAT) and for revenue calculation. These parameters are set up by using the **General ledger parameters** form. For more information, see [(RUS) Restoring VAT payments to a budget](rus-restoring-vat-payments-to-a-budget.md).

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click the **Sales tax** link.

3.  In the **Revenue calculation method** field, select the method of revenue calculation to use to restore VAT amounts. The following options are available:
    
      - **All** – All export invoices for the period are included when revenue is calculated.
    
      - **Indirect** – Export invoices for undefined purchases for the period are included when revenue is calculated.

4.  In the **VAT restoring method** field, select a calculation method. The following options are available:
    
      - **Mixed** – All indirect costs for the current period are multiplied by the calculated factor. Direct costs are calculated based on the proportion of sold and purchased quantities, regardless of the period of their receipt.
    
      - **By factor** – Both direct and indirect costs for the current period are multiplied by the calculated coefficient.

## See also

[(RUS) Calculate restored VAT and revenue amounts](rus-calculate-restored-vat-and-revenue-amounts.md)

  


