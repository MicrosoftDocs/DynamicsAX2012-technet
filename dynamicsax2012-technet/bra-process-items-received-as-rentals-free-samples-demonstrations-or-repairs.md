---
title: (BRA) Process items received as rentals, free samples, demonstrations, or repairs
TOCTitle: (BRA) Process items received as rentals, free samples, demonstrations, or repairs
ms:assetid: 31803499-55d1-4d66-b241-5505e98125ea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863722(v=AX.60)
ms:contentKeyID: 50396405
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- repair
- BRA
- Brazil
- demonstration
- free sample
- process goods
- rental
---

# (BRA) Process items received as rentals, free samples, demonstrations, or repairs [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In some circumstances, taxes may not be involved when you receive items as rentals or free samples, or when items are received for demonstration purposes or repairs. Use the following procedure to process the items that are received as rentals, free samples, demonstrations, or repairs.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>

    
    2.  In the **Vendor** field group, in the **Posting profile** field, select the vendor posting profile for the operation type.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**. Create ICMS and IPI sales tax codes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. Click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the sales tax group.

4.  For taxes that are exempt, in the **Taxation code** field, select a taxation code for which the fiscal value is set to **2. without credit/debit (exempt or not taxable)** in the **Fiscal value** field in the **Taxation code** form.

5.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

6.  To record this operation, create a purchase order that has the operation type and sales tax group that you created. For more information, see[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md)

7.  Post the purchase order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj911277\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

