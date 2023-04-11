---
title: (BRA) Set up the purchase of electricity
TOCTitle: (BRA) Set up the purchase of electricity
ms:assetid: ae91ac77-8f5f-4088-aa39-d3774c651b34
ms:mtpsurl: https://technet.microsoft.com/library/JJ863732(v=AX.60)
ms:contentKeyID: 50396415
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- electricity
- purchase of electricity
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the purchase of electricity 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax credit on the purchase of electricity varies based on state regulations. Legal entities can claim the ICMS tax credit either on the total amount that is spent on the purchase of electricity or on the amount that is spent on these purchases for the manufacturing area of the legal entity. The purchase of electricity is exempt from Imposto sobre Produtos Industrializados (IPI) tax.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup for the purchase of electricity:
    
    1.  Clear the **Create inventory movements** check box to specify that the operation type does not generate inventory movement.
    
    2.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    3.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create the sales tax code for ICMS for the purchase of electricity. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click the **Calculation** FastTab, and then in the **Origin** field, select **Percentage of net amount** as the method of calculation for the selected sales tax code. Then, in the **Marginal base** field, select **Net amount per line** as the type of amount that is used to calculate the sales tax code.

4.  Click **Values** to open the **Values** form. In the **Tax reduction pct** field, of the total amount that is spent on the purchase of electricity, enter the percentage that is exempt from ICMS tax.
    
    For example, you purchase electricity for BRL 200.00 at a rate of 10 percent ICMS, and only 50 percent of the electricity is used in the manufacturing area. You must create an ICMS tax code that has a rate of 10 percent, and then enter the tax reduction percentage as 50 percent.

5.  Close the forms.

6.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

7.  To record this operation, create a purchase order that has the operation type and ICMS sales tax code that you created. .

8.  Post the purchase order.For more information,see[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md)

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\))

[Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md)

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[Values of sales tax codes (form)](https://technet.microsoft.com/library/aa500790\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

  


