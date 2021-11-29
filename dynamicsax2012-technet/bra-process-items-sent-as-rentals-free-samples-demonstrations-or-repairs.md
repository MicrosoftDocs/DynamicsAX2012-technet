---
title: (BRA) Process items sent as rentals, free samples, demonstrations, or repairs
TOCTitle: (BRA) Process items sent as rentals, free samples, demonstrations, or repairs
ms:assetid: 48983ca0-3f21-42a5-8130-0176b9a77efc
ms:mtpsurl: https://technet.microsoft.com/library/JJ863724(v=AX.60)
ms:contentKeyID: 50396407
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- demonstration
- process goods
- rental
- free samples
- repairs
audience: Application User
ms.search.region: Brazil
---

# (BRA) Process items sent as rentals, free samples, demonstrations, or repairs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In some circumstances, taxes may not be involved when you send items as rentals or free samples, or when items are sent for demonstration purposes or repairs. Use the following procedure to process items sent as rentals, free samples, demonstrations, or repairs.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>

    
    2.  In the **Customer** field group, in the **Posting profile** field, select the customer posting profile for the operation type.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**. Create ICMS and IPI sales tax codes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. In the **Sales tax groups** form, click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the sales tax group.
    

    > [!NOTE]
    > <P>For taxes that are exempt, in the <STRONG>Taxation code</STRONG> field on the <STRONG>Setup</STRONG> FastTab, you must select a taxation code for which the fiscal value is set to <STRONG>2. without credit/debit (exempt or not taxable)</STRONG> in the <STRONG>Fiscal value</STRONG> field in the <STRONG>Taxation code</STRONG> form.</P>



4.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

5.  To record this operation, create a sales order that has the operation type and sales tax group that you created. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

6.  Post the sales order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/library/jj663981\(v=ax.60\))

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/library/jj911252\(v=ax.60\))

  


