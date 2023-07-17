---
title: (EEUR) Retail customer invoices and return sales orders in Eastern European countries/regions
TOCTitle: (EEUR) Retail customer invoices and return sales orders in Eastern European countries/regions
ms:assetid: 4585c22a-a557-45d0-9312-81f4df2c76e4
ms:mtpsurl: https://technet.microsoft.com/library/Dn268480(v=AX.60)
ms:contentKeyID: 54917019
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustTable
- Forms.RetailStoreTable
- EastEU – 00008
- LT – 00004
- LV - 00005
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Retail customer invoices and return sales orders in Eastern European countries/regions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the following information for customer invoices and return sales orders that are generated in Retail POS:

  - Use sales tax groups to process returns by using return sales orders. Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**. Click **Posting**, and then select the **Use sales tax group for returns** check box. For more information, see [Retail parameters (form)](https://technet.microsoft.com/library/hh597194\(v=ax.60\)).
    

    > [!NOTE]
    > <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 1 for AX 2012 R2.</P>

    
      - To specify the sales tax group for returns that are made by a customer, in the **Customers** form, on the **Retail** FastTab, in the **Sales tax group for returns** field, select a sales tax group. For more information, see [Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\)). When you post a return sales order for a customer, the return sales order line is updated with the sales tax group for returns that is specified in the **Customers** form.
        
        –or–
        
        To specify a sales tax group for returns that are made at a retail POS by a customer, in the **Stores** form, on the **General** FastTab, in the **Sales tax group for returns** field, select a sales tax group. For more information, see [Stores (form)](https://technet.microsoft.com/library/hh580646\(v=ax.60\)). When you post a return sales order for a customer of a retail store, the return sales order line is updated with the sales tax group for returns that is specified in the **Stores** form.

  - Use the posting date of a retail customer invoice or a return sales order as the sales date of the invoice or return if the invoice or return does not have a default sales date. Click **Retail** \> **Setup** \> **Parameters** \> **Retail parameters**. Click **Posting**, and then select the **Use posting date as sales date** check box.

  - Use the number range that is provided by the tax authorities to number Latvian and Lithuanian customer invoices and return sales orders. Click **Organization administration** \> **Common** \> **Number sequences** \> **Registers** \> **Invoice numbering setup**. Select the **Retail** check box for the number sequence line that is used to number the customer invoices.

  


