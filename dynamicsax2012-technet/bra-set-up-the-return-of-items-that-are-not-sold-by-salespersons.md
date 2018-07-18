---
title: (BRA) Set up the return of items that are not sold by salespersons
TOCTitle: (BRA) Set up the return of items that are not sold by salespersons
ms:assetid: 7d496306-8149-4af9-9540-25750b1e92c5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863726(v=AX.60)
ms:contentKeyID: 50396409
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- not sold by salesperson
- return of goods
- salespersons
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the return of items that are not sold by salespersons 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Legal entities that employ salespersons for door-to-door sales issue fiscal documents that have Imposto sobre Produtos Industrializados (IPI) and Imposto sobre Circulação de Mercadorias e Serviços (ICMS) taxes. When a salesperson sells items, you can create a new sales order.

Items that are not sold by a salesperson are returned. In this case, the remittance return from the salesperson for the sale of items involves recording a purchase order for the items that are returned. This operation is performed by using the transit warehouse, because the operation resembles a transfer of stock from one warehouse to another warehouse.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
      - Select the **Create inventory movements** check box to specify that the operation type generates inventory movement.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> tab in the <STRONG>Item model groups</STRONG> form.</P>

    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create ICMS and IPI sales tax codes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md)

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group, and then attach the ICMS and IPI sales tax codes to the sales tax group.

4.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal document source texts**. Create fiscal document source text for the fiscal document. For more information, see [(BRA) Set up a fiscal document source text](bra-set-up-a-fiscal-document-source-text.md).

5.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

6.  To record this operation, create a purchase order that has the operation type, sales tax group, and fiscal document source text that you created. For more information, see[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md) .

7.  Post the purchase order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/en-us/library/jj663934\(v=ax.60\))

  


