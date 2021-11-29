---
title: (RUS) Calculate the storage service amount for an item and generate a storage report
TOCTitle: (RUS) Calculate the storage service amount for an item and generate a storage report
ms:assetid: bbcd4309-9cb4-406e-9fa6-59e8ef0ca5f9
ms:mtpsurl: https://technet.microsoft.com/library/JJ853219(v=AX.60)
ms:contentKeyID: 50396500
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate the storage service amount for an item and generate a storage report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Storage calculation operations** form to calculate the storage service amount for items that are in bailment. You can create storage transaction journals for each item, warehouse, owner, and contract. Each transaction journal contains details of the item that is stored, the storage period, the price agreement, and the calculation method. You can also generate a storage report in Microsoft Excel forma.

1.  Click **Accounts receivable** \> **Periodic** \> **Bailment** \> **Storage calculation**.
    
    –or–
    
    Click **Accounts receivable** \> **Periodic** \> **Bailment** \> **Creation of storage calculation**.

2.  Click **New** to open the **Operation of storage calculation** form.

3.  In the **Date** field, select the ending date of the storage period. In the **Warehouse** field, select the warehouse that stores the item.

4.  In the **Customer account** field, select the account number of the bailor.

5.  In the **Sales agreement ID** field, select the sales agreement number for bailment.

6.  Click **OK** to create a new storage transaction journal.
    
    In the **Storage calculation operations** form, on the **General** tab, the **Currency** field displays the currency code as defined by the International Organization for Standardization (ISO).

7.  Click **Lines** to open the **Lines of storage calculation operation** form. You can delete the lines of operation. You can also run the procedure for calculating operations lines of storage again by using a different set of criteria. For more information, see [(RUS) Lines of storage calculation operation (form)](https://technet.microsoft.com/library/jj856119\(v=ax.60\)).

8.  Click **Print** \> **Storage report** to generate the storage report. You can also create a storage transaction journal by using the **Operation of storage calculation** form.

## See also

[(RUS) Storage calculation operations (form)](https://technet.microsoft.com/library/jj678512\(v=ax.60\))

  


