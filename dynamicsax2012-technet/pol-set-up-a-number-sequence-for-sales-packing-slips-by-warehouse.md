---
title: (POL) Set up a number sequence for sales packing slips by warehouse
TOCTitle: (POL) Set up a number sequence for sales packing slips by warehouse
ms:assetid: 4a2000a1-c13c-4d80-956b-2257074aacb9
ms:mtpsurl: https://technet.microsoft.com/library/JJ678192(v=AX.60)
ms:contentKeyID: 49386915
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up a number sequence for sales packing slips by warehouse 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a number sequence for sales packing slips by warehouse in the **Accounts receivable parameters** form. You can number delivery documents separately for each warehouse.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the left pane, click **Updates**. Select the **Independent delivery note numbering** check box.

3.  In the left pane, click **Number sequences**. Select a number sequence for the **Packing slip** reference type.

4.  Click **Warehouses**.

5.  In the **Sales - delivery note numbering** form, in the **Warehouse** field, select a warehouse.

6.  In the **Number sequence code** field, enter a packing slip number sequence codes for the selected warehouse.

7.  Repeat step 6 for each warehouse.

8.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>You can also set up delivery document numbering by warehouse for a sales order. To do this, select a specific warehouse in the <STRONG>Packing slip</STRONG> form. After you post a packing slip, the order status will not change to <STRONG>Delivered</STRONG> or <STRONG>Received</STRONG> in the sales order until all sales lines for all warehouses are posted for the sales order.</P>



## See also

[(POL) Set up a number sequence for purchase product receipts by warehouse](pol-set-up-a-number-sequence-for-purchase-product-receipts-by-warehouse.md)

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/library/jj678183\(v=ax.60\))

[Packing slip journal (form)](https://technet.microsoft.com/library/aa548967\(v=ax.60\))

  


