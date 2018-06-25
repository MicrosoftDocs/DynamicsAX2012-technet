---
title: (BRA) Record the purchase of a fixed asset
TOCTitle: (BRA) Record the purchase of a fixed asset
ms:assetid: 90801784-8ef5-4631-a0cb-c1b9249087b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ863728(v=AX.60)
ms:contentKeyID: 50396411
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed asset
- BRA
- Brazil
- purchase fixed asset
---

# (BRA) Record the purchase of a fixed asset [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can record the purchase of a fixed asset by using the **Purchase order** form.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**. Create an operation type that has the following setup:
    
    1.  Select the **Create customer/vendor transactions** check box to specify that the operation type creates customer or vendor transactions.
    
    2.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.
    
    3.  In the **Vendor** field group, in the **Posting profile** field, select the vendor posting profile for the operation type to account for the deferment of Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax.
    
    For more information, see [(BRA) Set up operation types](bra-set-up-operation-types.md).

2.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Create sales tax codes for ICMS and Imposto sobre Produtos Industrializados (IPI) taxes. The ICMS tax code that you create must specify the actual value, and the IPI tax code must have a value of 0 (zero). For more information, see [(BRA) Set up tax codes](bra-set-up-tax-codes.md).

3.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Create a sales tax group. In the **Sales tax groups** form, click the **Setup** FastTab, and then add the ICMS and IPI tax codes to the sales tax group. For exemption from taxes, in the **Taxation code** field, select a taxation code for which the fiscal value is set to **1. with credit/debit** in the **Fiscal value** field in the **Taxation code** form.

4.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

5.  To record this operation, create a purchase order for the fixed asset that has the operation type and sales tax group that you created. For more information, see [(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md) .

6.  In the **Purchase order** form, on the **Action Pane**, click **Line view**.

7.  Click the **Line details** FastTab, and then click the **Fixed assets** tab

8.  In the **Fixed asset number** and **Value model** fields, select the fixed asset and value model for the fixed asset.

9.  Post the purchase order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/en-us/library/jj822922\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/en-us/library/jj663982\(v=ax.60\))

[(BRA) Sales tax groups (modified form)](https://technet.microsoft.com/en-us/library/jj663981\(v=ax.60\))

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/en-us/library/jj911277\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

