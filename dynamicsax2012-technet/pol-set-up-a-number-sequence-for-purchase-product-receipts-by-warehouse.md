---
title: (POL) Set up a number sequence for purchase product receipts by warehouse
TOCTitle: (POL) Set up a number sequence for purchase product receipts by warehouse
ms:assetid: e866955a-5e01-4631-b0f2-1ee88954ea0c
ms:mtpsurl: https://technet.microsoft.com/library/JJ711321(v=AX.60)
ms:contentKeyID: 49387140
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up a number sequence for purchase product receipts by warehouse 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up a number sequence for purchase product receipts by warehouse in the **Accounts payable parameters** form. You can number delivery documents separately for each warehouse.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  In the **Accounts payable parameters** form, in the left pane, click **Number sequences**.

3.  In the **Number sequence code** field, select a number sequence for the **Internal product receipt** reference type.

4.  Click **Warehouses**.

5.  In the **Purchase – delivery note numbering** form, in the **Warehouse** field, select a warehouse.

6.  In the **Number sequence code** field, enter a product receipt number sequence code for the selected warehouse.

7.  Repeat step 6 for each warehouse.

8.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>You can also set up delivery document numbering by warehouse for a purchase order. To do this, select a specific warehouse in the <STRONG>Posting product receipt</STRONG> form. After you post a product receipt, the order status of the purchase order line will not change to <STRONG>Delivered</STRONG> or <STRONG>Received</STRONG> until all purchase lines for all warehouses are posted for the purchase order.</P>



## See also

[(POL) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj678134\(v=ax.60\))

[Purchase posting (form)](https://technet.microsoft.com/library/aa587152\(v=ax.60\))

  


