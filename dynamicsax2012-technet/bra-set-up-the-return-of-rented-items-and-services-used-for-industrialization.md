---
title: (BRA) Set up the return of rented items and services used for industrialization
TOCTitle: (BRA) Set up the return of rented items and services used for industrialization
ms:assetid: 96bfbded-9536-4445-847c-e0b9a0e0aeac
ms:mtpsurl: https://technet.microsoft.com/library/JJ863730(v=AX.60)
ms:contentKeyID: 50396412
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- return of goods
- hiring basis
- industrialization purpose
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the return of rented items and services used for industrialization 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Items and services that are rented and used for industrialization may be exempt from Imposto sobre Circulação de Mercadorias e Serviços (ICMS) and Imposto sobre Produtos Industrializados (IPI) taxes. The legal entity that receives the items or services can handle the receipt as a symbolic remittance or as an actual remittance that does not involve the calculation of taxes. For a symbolic remittance, there is no inventory movement. However, for an actual remittance, you must register the movement of inventory.

You can set up operation types, sales tax codes, and item sales tax groups for this operation. You can then create a purchase order to register this operation.

Use this procedure to set up the operation type, sales tax codes, and item sales tax group for this operation. You can then create a purchase order to record this operation.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
      - If the operation is an actual remittance, select the **Create inventory movements** check box to specify that the operation type generates inventory movement. If the operation is a symbolic remittance, clear the **Create inventory movements** check box to specify that the operation type does not generate inventory movement.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> tab in the <STRONG>Item model groups</STRONG> form.</P>

    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**. Create ICMS and IPI sales tax codes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create a sales tax group. In the **Item sales tax groups** form, click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the item sales tax group. In the **Taxation code** field, select the taxation code for which the fiscal value is set to **2. without credit/debit (exempt or not taxable)** in the **Fiscal value** field in the **Taxation code** form.

4.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

5.  To record actual remittance, create a purchase order that has the operation type and item sales tax group that you created. To record a symbolic remittance, create a purchase order that has the operation type that you created. Taxes are not calculated for a symbolic remittance. For more information, see [(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md).

6.  Post the purchase order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj682105\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

  


