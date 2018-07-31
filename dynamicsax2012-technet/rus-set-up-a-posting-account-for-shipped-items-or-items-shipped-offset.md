---
title: (RUS) Set up a posting account for shipped items or items shipped offset
TOCTitle: (RUS) Set up a posting account for shipped items or items shipped offset
ms:assetid: b556c7ef-8784-4d8b-8ddd-883c8d334890
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923583(v=AX.60)
ms:contentKeyID: 52075427
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a posting account for shipped items or items shipped offset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Posting** form to set up a posting account for shipped items or items shipped offset.

1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Posting**.

2.  Select a type of sales order account from the following options:
    
      - **Goods shipped** – The ledger account that the ledger transactions for shipped items are posted to.
    
      - **Goods shipped offset** – The ledger account that the ledger transactions for shipped items offset are posted to.

3.  Press CTRL+N to create a new line.

4.  In the **Item code** field, select an item relationship from the following options:
    
      - **Table** – The posting to an account in the general ledger applies only to a specific item number, which is specified in the **Item relation** field.
    
      - **Group** – The posting to an account in the general ledger applies only to a specific item group, which is specified in the **Item relation** field.
    
      - **All** – The item code applies to all items.

5.  In the **Item relation** field, select an item or item group. This field is available only if **Table** or **Group** is selected in the **Item code** field.

6.  In the **Account code** field, select an account relation from the following options:
    
      - **Table** – The account relationship applies to a specific customer. If you select **Table**, only transactions of the vendor or customer account that is specified in the **Account relation** field are posted to the general ledger.
    
      - **Group** – The account relationship applies to a list of customer groups. If you select **Group**, transactions of the vendor or customer group that is specified in the **Item relation** field are posted to the general ledger.
    
      - **All** – The account relationship applies to all customers.

7.  In the **Account relation** field, select a customer account or customer group to set up an account relationship for. This field is available only if **Table** or **Group** is selected in the **Account code** field.

8.  In the **Sales tax group** field, select a sales tax group.

9.  In the **Main account** field, select a ledger account number.

## See also

[(RUS) Item posting (modified form)](https://technet.microsoft.com/en-us/library/jj733204\(v=ax.60\))

  


