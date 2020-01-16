---
title: (RUS) Set up a posting profile
TOCTitle: (RUS) Set up a posting profile
ms:assetid: 478e2713-9391-4008-989a-189f4080ec32
ms:mtpsurl: https://technet.microsoft.com/library/JJ733215(v=AX.60)
ms:contentKeyID: 49685183
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a posting profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create or update a posting record in the **Inventory profile - posting profile** form, the inventory transaction combination that corresponds to the specified settings of the inventory profile is activated.


> [!NOTE]
> <P>If you select <STRONG>Type</STRONG> in the <STRONG>Inventory profile relation</STRONG> field, the <STRONG>Kind of activity</STRONG> field is activated. If you select <STRONG>Profile</STRONG>, the <STRONG>Inventory profile</STRONG> field is activated.</P>



1.  Click **Inventory management** \> **Setup** \> **Posting** \> **Inventory profile - posting profile**.

2.  Create a posting profile for the inventory profile record.

3.  In the **Inventory profile relation** field, select the inventory profile relationship from the following options:
    
      - **Profile** – Assign the ledger account to an inventory profile.
    
      - **Type** – Assign the ledger account to a kind of activity.
    
      - **All** – Assign the ledger account to all inventory profiles and all kinds of activities.

4.  If you select **Type** in the **Inventory profile relation** field, in the **Kind of activity** field, select **Basic**, **Commission agent**, **Principal's agent**, or **Bailee** as the profile activity type.
    
    –or–
    
    If you select **Profile** in the **Inventory profile relation** field, in the **Inventory profile** field, enter the inventory profile.

5.  In the **Vendor posting profile** field, enter the vendor posting profile for the selected inventory profile.

6.  In the **Customer posting profile** field, enter the customer posting profile for the selected inventory profile.

## See also

[(RUS) Activate inventory transaction combinations](rus-activate-inventory-transaction-combinations.md)

[(RUS) Activate transaction combinations (modified form)](https://technet.microsoft.com/library/jj733228\(v=ax.60\))

  


