---
title: (BRA) Process the return of purchased items
TOCTitle: (BRA) Process the return of purchased items
ms:assetid: 893bbcbb-8cc9-4482-b9ef-cad21185bcb4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863727(v=AX.60)
ms:contentKeyID: 50396410
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- purchased goods
- return of purchased goods
---

# (BRA) Process the return of purchased items [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Legal entities can record the return of items that they purchased from a vendor. To record a return, a legal entity creates a sales fiscal document that has transactions that resemble the transactions on the original purchase fiscal document. The legal entity can also generate a fiscal document to record the transaction for the purchase return.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>

    
    2.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    3.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.
    
    4.  In the **Customer** field group, in the **Posting profile** field, select the customer posting profile for the operation type.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

3.  To record this operation, create a sales order that has the operation type that you created. The sales tax groups and posting profile for the return fiscal document must be the same as the sales tax groups and posting profile for the original fiscal document. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

4.  Post the sales order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj911252\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

