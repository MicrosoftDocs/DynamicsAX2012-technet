---
title: (BRA) Set up the purchase of freight services
TOCTitle: (BRA) Set up the purchase of freight services
ms:assetid: 4875187e-361d-46f9-91b3-6ebde3e56b5e
ms:mtpsurl: https://technet.microsoft.com/library/JJ863725(v=AX.60)
ms:contentKeyID: 50396408
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- freight services
- purchase freight services
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the purchase of freight services 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Some legal entities claim the Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax credit on the purchase of freight services. To set up the purchase of freight services:

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup for the purchase of freight service:
    
    1.  Clear the **Create inventory movements** check box to specify that the operation type does not generate inventory movement.
    
    2.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    3.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create ICMS and IPI sales tax codes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create an item sales tax group. Click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the item sales tax group.
    

    > [!NOTE]
    > <P>For exemption from IPI tax, on the <STRONG>Setup</STRONG> FastTab, in the <STRONG>Taxation code</STRONG> field for the IPI tax code, select the taxation code for which the fiscal value is set to <STRONG>2. without credit/debit (exempt or not taxable)</STRONG> in the <STRONG>Fiscal value</STRONG> field in the <STRONG>Taxation code</STRONG> form.</P>



4.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

5.  To record this operation, create a purchase order that has the operation type and item sales tax group that you created. For more information, see .

6.  Post the purchase order.For more information,see[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md)

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj682105\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

  


