---
title: Set up sellable days for a customer
TOCTitle: Set up sellable days for a customer
ms:assetid: 3d520b80-d319-44ab-a1d1-c94d0c4deb5c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh352197(v=AX.60)
ms:contentKeyID: 36687830
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- define sellable days
- sellable days
- sellable period
- set up sellable days
---

# Set up sellable days for a customer [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up the number of days that a customer defines as the sellable period for a product, item group, or all items. The sellable period is the number of days that a product is considered to be sellable. The period starts on the date the product is received, and ends on the best before date or the shelf life date.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select the customer account.

3.  On the **Action Pane**, on the **Sell** tab, in the **Setup** group, select **Sellable days**.

4.  Press CTRL+N to add a new line.

5.  In the **Item code** field, select an option to define whether the sellable days apply to a specific item, item group, or all items for this customer:
    
      - **Table** — Applies to a specific item.
    
      - **Group** — Applies to an item group.
    
      - **All** — Applies to all items.

6.  In the **Item relation** field, select the item or item group. If you selected the item code **All**, this field is not available.

7.  In the **Sellable days** field, enter the number of days that make up the sellable period.

## See also

[Sellable days by customer (form)](https://technet.microsoft.com/en-us/library/hh328638\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

