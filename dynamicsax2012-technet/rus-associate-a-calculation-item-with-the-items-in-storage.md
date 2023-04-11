---
title: (RUS) Associate a calculation item with the items in storage
TOCTitle: (RUS) Associate a calculation item with the items in storage
ms:assetid: 60561e09-5884-4c39-a955-6cd77f7cab88
ms:mtpsurl: https://technet.microsoft.com/library/JJ665440(v=AX.60)
ms:contentKeyID: 49387528
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Associate a calculation item with the items in storage 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Storage calculation setup** form to associate a calculation item with the items that are in storage. You can calculate the storage service amount for items by using the calculation item that is associated with the item. For more information, see [(RUS) Calculation of the storage service amount for items](rus-calculation-of-the-storage-service-amount-for-items.md).

1.  Click **Accounts receivable** \> **Setup** \> **Bailment** \> **Storage calculation setup**.

2.  In the **Storage calculation item** field, select a calculation item that is used to calculate the storage service amount.

3.  In the **Item code** field, select the criterion that is used to select items, from the following options:
    
      - **Table** – Associate a calculation item with a specific item.
    
      - **Group** – Associate a calculation item with a specific item group.
    
      - **All** – Associate a calculation item with all items.

4.  In the **Code** field, select the user-defined code that is assigned to the item or item group that is in storage.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Item code</STRONG> field.</P>



5.  In the **Warehouse relation** field, select the criterion that is used to select warehouses, from the following options:
    
      - **Table** – The warehouse relation is for a specific warehouse.
    
      - **Group** – The warehouse relation is for a specific site.
    
      - **All** – The warehouse relation is for all warehouses.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Table</STRONG> or <STRONG>Group</STRONG> in the <STRONG>Warehouse relation</STRONG> field.</P>



6.  In the **Customer relation** field, select the criterion that is used to select customer accounts, from the following options:
    
      - **Table** – The customer relation is for a specific customer.
    
      - **Group** – The customer relation is for a specific customer group.
    
      - **All** – The customer relation is for all customers.

7.  In the **Account relation** field, select a customer account or customer group for which the items are stored. This field is available only if you select **Table** or **Group** in the **Customer relation** field.

8.  In the **Agreement relation** field, select the criterion that is used to select contracts, from the following options:
    
      - **Table** – The agreement relation is for a specific agreement.
    
      - **All** – The agreement relation is for all customers or vendors.

9.  In the **Code** field, select an agreement that is created for bailment. This field is available only if you select **Table** or **Group** in the **Agreement relation** field.Click the **General** tab.

10. Click the **General** tab.

11. In the **From date** and **To date** fields, select the starting date and ending date of the storage period.

## See also

[(RUS) Storage calculation setup (form)](https://technet.microsoft.com/library/jj733408\(v=ax.60\))

  


