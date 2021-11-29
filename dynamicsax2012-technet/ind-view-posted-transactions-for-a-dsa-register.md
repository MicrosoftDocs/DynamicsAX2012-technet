---
title: (IND) View posted transactions for a DSA register
TOCTitle: (IND) View posted transactions for a DSA register
ms:assetid: 198b00e3-fdde-4c2f-94b8-d03fa53c4332
ms:mtpsurl: https://technet.microsoft.com/library/JJ664524(v=AX.60)
ms:contentKeyID: 49385602
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- DSA
- posted transactions
audience: Application User
ms.search.region: India
---

# (IND) View posted transactions for a DSA register 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can view details of items that excise duty is levied on in the **DSA details** form. You can view the item code, the opening balance of the quantity of item, the quantity of the manufactured item, the quantity of the item that is sold, the quantity of the available balance of the item, and the excise duty for the transaction.

In Microsoft Dynamics AX 2012, items and products are referred to interchangeably. A product name is always associated with an item ID. The main concepts that are associated with items are product, product master, and product variant. For more information, see [View items](view-items.md).


> [!NOTE]
> <P>The daily stock account (DSA) register is updated for products that have <STRONG>Production</STRONG> selected in the <STRONG>Default order type</STRONG> field on the <STRONG>Default order settings</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/hh209541(v=ax.60)">Order settings (form)</A>.</P>



1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

2.  Select the Excise control code (ECC) number for the company's address in the **ECC number** field.

3.  Select the tax settlement period for the selected ECC number in the **Sales tax settlement period** field.

4.  Select the DSA excise register in the **Register** field to view the DSA transactions.

5.  Select the starting and ending dates for the period in the **From date** and **To date** fields.

6.  Click **OK** to open the **DSA transactions** form.

7.  Click **Inquiries** \>**DSA details**.

8.  You can view the following details:
    
      - The date of the transaction in the **Date** field.
    
      - The starting-balance of the quantity of the item available in the DSA register in the **Opening balance** field.
    
      - The quantity of the item used in the production process in the **Manufactured quantity** field.
    
      - The quantity of item sold in the **Issue quantity** field.
    
      - The quantity of items available in the **Total available** field.
        

        > [!NOTE]
        > <P>The Total available = Opening balance + Manufacture quantity – Issue quantity.</P>

    
      - The total excise duty in the **Tax amount** field. The value in this field is the total excise duty calculated on the issued-quantity that is specified in the sales order for BOM type of item.

## See also

[(IND) DSA details (form)](https://technet.microsoft.com/library/jj664573\(v=ax.60\))

[(IND) Excise register inquiry (form)](https://technet.microsoft.com/library/jj710979\(v=ax.60\))

  


