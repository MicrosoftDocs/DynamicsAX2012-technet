---
title: (BRA) Set up a tax matrix
TOCTitle: (BRA) Set up a tax matrix
ms:assetid: 7ec568e6-dbd0-4d5f-a50c-ca4c68df0060
ms:mtpsurl: https://technet.microsoft.com/library/JJ943750(v=AX.60)
ms:contentKeyID: 51028416
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- tax
- BRA
- Brazil
- tax matrix
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up a tax matrix 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the sales tax group and item sales tax group that are used in sales, purchase, or inventory movement transactions. The tax groups for sales, purchase, or inventory transactions are determined based on the combination of the Código fiscal de operações e prestações (CFOP ) group, item, item group, customer, customer group, vendor, vendor group, fiscal establishment, or fiscal establishment group.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Taxes matrix**.

2.  Create a tax matrix.

3.  In the **Fiscal establishment group** field, select the group for the fiscal establishment.
    

    > [!NOTE]
    > <P>The tax groups that are available depend on the fiscal establishment group and CFOP code.</P>



4.  In the **CFOP group** field, select a CFOP group.

5.  In the **Type** field, select **Customer**, **Vendor**, or **Fiscal establishment** as the account type.

6.  In the **Account code** field, select one of the following options to indicate the account code for the selected account type:
    
      - **Table** – Set up the tax matrix for a single customer account, vendor account, or fiscal establishment.
    
      - **Group** – Set up the tax matrix for a customer group or vendor group.
    
      - **All** – Set up the tax matrix for all customers or all vendors.

7.  In the **Account relation** field, select the customer account, customer group, vendor account, or vendor group that the tax matrix applies to. Alternatively, enter the identification code of the fiscal establishment that the tax matrix applies to. This field is determined by the selections in the **Type** and **Account code** fields.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Account code</STRONG> field.</P>



8.  In the **Item code** field, select one of the following options to indicate the item code that the tax matrix applies to:
    
      - **Table** – Apply the tax matrix to a single item.
    
      - **Group** – Apply the tax matrix to an item group.
    
      - **All** – Apply the tax matrix to all items.

9.  In the **Item relation** field, select the item number or item group.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Item code</STRONG> field.</P>



10. Select the **Service items** check box to use tax groups for items of type **Service** that do not have a CFOP code. The defined tax groups are used as default tax groups on the sales or purchase orders for services.

11. Select the **Free text invoice** check box to use the tax groups as default tax groups for free text invoices for the customer, customer group, or all customers, based on the value that is selected in the **Account code** and **Account relation** fields.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Customer</STRONG> in the <STRONG>Type</STRONG> field.</P>



12. In the **Sales tax group** field, select the default sales tax group for the combination of the selected CFOP group, item, item group, customer, customer group, vendor, vendor group, fiscal establishment, or fiscal establishment group.

13. In the **Item sales tax group** field, select the default item sales tax group for the combination of the selected CFOP group, item, item group, customer, customer group, vendor, vendor group, fiscal establishment, or fiscal establishment group.

## See also

[(BRA) Taxes matrix (form)](https://technet.microsoft.com/library/jj923368\(v=ax.60\))

[(BRA) CFOP groups (form)](https://technet.microsoft.com/library/jj923344\(v=ax.60\))

  


