---
title: (BRA) Set up the purchase of items with anticipated invoicing
TOCTitle: (BRA) Set up the purchase of items with anticipated invoicing
ms:assetid: ee94f988-3e8c-4db2-bec1-173092cd670a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863742(v=AX.60)
ms:contentKeyID: 50396425
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- anticipated invoicing
- purchase of goods
---

# (BRA) Set up the purchase of items with anticipated invoicing [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Brazil, a purchase of items that uses anticipated invoicing occurs in two phases. In the first phase, you can issue a fiscal document without generating any physical and financial movement of inventory. In this phase, only the vendor balance is updated. In the second phase, when the actual delivery of items occurs, you can generate the inventory transactions and Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax transactions.

## Issue a fiscal document and update the balance

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Clear the **Create inventory movements** check box to specify that the operation type does not generate inventory movement.
    
    2.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    3.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create sales tax codes for all taxes that apply to this operation, except the ICMS tax. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. Click the **Setup** FastTab, and then add all the sales tax codes except the ICMS tax code.

4.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create an item sales tax group, and attach all the sales tax codes except the ICMS tax code.

5.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

6.  To record this operation, create a purchase order that has the operation type, sales tax group, and item sales tax group that you created..For more information,see[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md)

7.  Post the purchase order.

## Generate the tax transactions after delivery of the items

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
      - Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> tab in the <STRONG>Item model groups</STRONG> form.</P>



2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create sales tax codes for taxes that apply to this operation. These taxes include the ICMS tax.

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. Click the **Setup** FastTab, and then add all the sales tax codes.

4.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create an item sales tax group, and attach all the sales tax codes.

5.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

6.  To record this operation, create a purchase order that has the operation type, sales tax group, and item sales tax group that you created.

7.  Post the purchase order.

## See also

[(BRA) Set up operation types](bra-set-up-operation-types.md)

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj911277\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

