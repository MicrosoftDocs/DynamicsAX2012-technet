---
title: (BRA) Process sales with future delivery
TOCTitle: (BRA) Process sales with future delivery
ms:assetid: eb69d0ea-2694-43dd-8bf8-c60d623d66b7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863741(v=AX.60)
ms:contentKeyID: 50396424
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- future delivery
- process sales
---

# (BRA) Process sales with future delivery [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Brazil, a sale of items that uses anticipated invoicing occurs in two phases. In the first phase, you can create a fiscal document for the payment that is received, but there is no movement of inventory. In the second phase, you can generate inventory transactions and Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax transactions when the actual delivery of items occurs.

## Create fiscal document for the payment

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    2.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create sales tax codes for all taxes that apply to this operation, except the ICMS tax. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. In the **Sales tax groups** form, click the **Setup** FastTab, and then add all the sales tax codes except the ICMS tax code.

4.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create an item sales tax group, and then attach all the sales tax codes except the ICMS tax to the item sales tax group.

5.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  To record this operation, create a sales order that has the operation type, sales tax group, and item sales tax group that you created. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

7.  Post the sales order.

## Generate tax transactions after delivery of the items

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
      - Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>



2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create sales tax codes for taxes that apply to this operation. These taxes include the ICMS tax.

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. In the **Sales tax groups** form, click the **Setup** FastTab, and then add all the sales tax codes.

4.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create an item sales tax group, and then attach all the sales tax codes to the item sales tax group.

5.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

6.  To record this operation, create a sales order that has the operation type, sales tax group, and item sales tax group that you created.

7.  In the **Sales order** form, click **Line view**, and then in the **Sales order lines** area, click **Sales order line** \> **From all**. In the **Copy from all** form, select the sales order that was posted in the first phase, and then click **OK**. The status of the sales order that was posted in the first phase is updated to **Open order** in the **Status** field on the **All sales orders** list page.

8.  Post the sales order.

## See also

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj682105\(v=ax.60\))

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales posting (modified form)](https://technet.microsoft.com/en-us/library/jj853383\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

