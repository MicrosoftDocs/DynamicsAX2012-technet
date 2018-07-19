---
title: (RUS) Set up an inventory profile
TOCTitle: (RUS) Set up an inventory profile
ms:assetid: 5e505fcb-0ddb-4364-9445-b7b5283b6cae
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733235(v=AX.60)
ms:contentKeyID: 49685198
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an inventory profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An inventory profile is used to track and report the movement of items, and the accounting of on-hand inventory quantities, based on the kind of activity that the company engages in. The general ledger transactions that correspond to inventory movements depend on the inventory profiles. The kind of activity refers to the following groups of inventory profiles:

  - **Unspecified** – No profile activity is specified for items.
    
    **Basic** – Sell or purchase items without any limits.

  - **Commission agent** – The commission agent sells items in his or her name on behalf of the company (principal). The commission agent receives a commission in exchange for selling the items, and is responsible for the price calculations for the end customers.

  - **Principal's agent** – The agent of the company (principal) sells items that belong to the company, and is not responsible for the calculations that are performed for the end customers.
    
    **Bailee** – The bailee receives items for storage purposes but does not have proprietary rights to the items.

A particular item may have various inventory profiles or various kinds of activity. The movements and on-hand quantities of this item are accounted for by using different inventory dimensions in inventory accounting and different general ledger accounts in financial accounting.

To use inventory profiles, you must set up the following information:

  - An inventory profile. For more information, see [(RUS) Inventory profiles (form)](https://technet.microsoft.com/en-us/library/jj733188\(v=ax.60\)).

  - Inventory transaction combinations. For more information, see [(RUS) Activate inventory transaction combinations](rus-activate-inventory-transaction-combinations.md).

  - An inventory posting. For more information, see [(RUS) Set up an inventory posting profile](rus-set-up-an-inventory-posting-profile.md).

  - The **Inventory profile** parameter in the **Accounts receivable parameters** form and the **Inventory and warehouse management parameters** form. For more information, see [(RUS) Set up inventory parameters](rus-set-up-inventory-parameters.md).

  - A dimension group for inventory dimensions.

  - Inventory profiles, vendors, or customer posting profiles. For more information, see, [(RUS) Inventory profiles (form)](https://technet.microsoft.com/en-us/library/jj733188\(v=ax.60\)) and [(RUS) Customer posting profiles (modified form)](https://technet.microsoft.com/en-us/library/jj678641\(v=ax.60\)).

  - Inventory profiles and kinds of activity, in the **Customers** form, **Vendors** form, **Purchase agreements** form, **Sales agreements** form, and **Warehouses** form. For more information, see [(RUS) Set up an inventory profile in the Customers form](rus-set-up-an-inventory-profile-in-the-customers-form.md), [(RUS) Set up an inventory profile in the Vendors form](rus-set-up-an-inventory-profile-in-the-vendors-form.md), and [(RUS) Set up an inventory profile in the Warehouses form](rus-set-up-an-inventory-profile-in-the-warehouses-form.md).

## Set up the inventory profile

Use the **Inventory profiles** form to set up a new inventory profile.

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Inventory profiles**.

2.  Create a record.

3.  In the **Inventory profile** field, enter the inventory profile.

4.  In the **Name** field, enter the name of the inventory profile.

5.  In the **Kind of activity** field, select **Basic**, **Commission agent**, **Principal's agent**, or **Bailee** as the kind of activity.

6.  Select the **Don’t match** check box to prevent automatic matching of on-hand inventory from this inventory profile with a compatible inventory profile.

7.  Click the **Matching priority** FastTab.

8.  Click **Up** or **Down** to change the priority of each inventory profile.

9.  Click the **Compatible inventory profiles** FastTab.
    

    > [!NOTE]
    > <P>For each inventory profile, you can define a corresponding compatible inventory profile.</P>



10. In the **Compatible** list and the **Other** list, add or remove inventory profiles as necessary.

11. Click **Up** or **Down** to increase or decrease the priority of the specified compatible inventory profile.

## Setting up a dimension group for inventory

You must set up a dimension group for the inventory profile. For more information, see [Product dimension groups (form)](https://technet.microsoft.com/en-us/library/hh227672\(v=ax.60\)), [Storage dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209317\(v=ax.60\)), and [Tracking dimension groups (form)](https://technet.microsoft.com/en-us/library/hh209465\(v=ax.60\)).

## See also

[(RUS) Activate transaction combinations (modified form)](https://technet.microsoft.com/en-us/library/jj733228\(v=ax.60\))

[(RUS) Customers (modified form)](https://technet.microsoft.com/en-us/library/jj853212\(v=ax.60\))

[(RUS) Set up a posting profile](rus-set-up-a-posting-profile.md)

  


