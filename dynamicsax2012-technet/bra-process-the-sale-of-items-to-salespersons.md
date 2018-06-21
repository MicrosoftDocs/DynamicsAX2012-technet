---
title: (BRA) Process the sale of items to salespersons
TOCTitle: (BRA) Process the sale of items to salespersons
ms:assetid: d6e62d6c-d0a2-443c-84ef-b887f4f58046
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863739(v=AX.60)
ms:contentKeyID: 50396421
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- sale of goods
---

# (BRA) Process the sale of items to salespersons [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Legal entities that employ salespersons for door-to-door sales can issue a customer fiscal document that has the Imposto sobre Circulação de Mercadorias e Serviços (ICMS) and Imposto sobre Produtos Industrializados (IPI) taxes for items that are delivered outside the establishment.

You can record the items that are issued to a salesperson by using a sales order, and you can record the items that are received from a salesperson by using a purchase order. You can create a new sales order when salespersons sell the items that are issued to them.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
      - Select the **Create inventory movements** check box to specify that the operation type generates inventory movement, and to record the physical and financial movement of inventory.
        

        > [!NOTE]
        > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>

    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create sales tax codes for ICMS and IPI taxes. For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. In the **Sales tax groups** form, click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the sales tax group.

4.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. Create an item sales tax group, and then attach the ICMS and IPI sales tax codes that you created.

5.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal document source texts**. Create a fiscal document source text for the sales order. For more information, see [(BRA) Set up a fiscal document source text](bra-set-up-a-fiscal-document-source-text.md).

6.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

7.  To record this operation, create a sales order that has the operation type, sales tax group, and item sales tax group that you created. For more information, see [(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md).

8.  In the **Sales order** form, click **Header view**. Then, on the **Action Pane**, on the **Sales order** tab, click **Fiscal document texts** to attach the fiscal document text that you created to the sales order. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).

9.  Post the sales order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj682105\(v=ax.60\))

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj911252\(v=ax.60\))

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/en-us/library/jj663934\(v=ax.60\))

[(BRA) Sales posting (modified form)](https://technet.microsoft.com/en-us/library/jj853383\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

