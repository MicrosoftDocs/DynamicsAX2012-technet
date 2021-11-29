---
title: (BRA) Process items and services rented for industrialization purposes
TOCTitle: (BRA) Process items and services rented for industrialization purposes
ms:assetid: b17a1d53-a7ac-46f5-870a-59e9da4b29a3
ms:mtpsurl: https://technet.microsoft.com/library/JJ863733(v=AX.60)
ms:contentKeyID: 50396416
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- process goods
- hiring basis
- industrialization
audience: Application User
ms.search.region: Brazil
---

# (BRA) Process items and services rented for industrialization purposes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a sales order to record the items that are rented for industrialization and manufacturing. You can also create a purchase order when the items are returned.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>

    
    2.  In the **Customer** field group, in the **Posting profile** field, select the customer posting profile for the operation type.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create ICMS and IPI sales tax codes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. In the **Sales tax groups** form, click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the sales tax group.

4.  In the **Taxation code** field, select the taxation code for which the fiscal value is set to **2. without credit/debit (exempt or not taxable)** in the **Fiscal value** field in the **Taxation code** form.

5.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  To record this operation, create a sales order that has the operation type and sales tax group that you created. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

7.  Post the sales order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/library/jj663981\(v=ax.60\))

  


