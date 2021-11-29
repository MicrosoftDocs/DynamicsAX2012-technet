---
title: Resolve conflicts in loyalty card numbers after upgrade (Retail)
TOCTitle: Resolve conflicts in loyalty card numbers after upgrade (Retail)
ms:assetid: ec4eb0cc-062c-475b-b9c2-ae46efbfa373
ms:mtpsurl: https://technet.microsoft.com/library/Dn715951(v=AX.60)
ms:contentKeyID: 62200027
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailLoyaltyConflictCard
- MsDynAx060.Forms.RetailLoyaltyConflictCard
---

# Resolve conflicts in loyalty card numbers after upgrade (Retail) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes how to resolve conflicts in Retail loyalty card numbers after you upgrade to Microsoft Dynamics AX 2012 R3. In previous releases of Microsoft Dynamics AX, you could use the same loyalty scheme ID and loyalty card numbers to represent different loyalty programs in different legal entities in your organization. For example, **Scheme1** in Contoso Canada could have different requirements and rewards than **Scheme1** in Contoso USA. Also, **Card1** could be issued to a Contoso Canada customer and also to a Contoso USA customer. In Microsoft Dynamics AX 2012 R3, you can have multiple loyalty programs, but the loyalty scheme ID and the loyalty card numbers must be unique.

After the upgrade process is completed, you must manually resolve conflicts in loyalty card numbers. We recommend that you resolve any conflicts before you process any loyalty transactions for new or existing customers.


> [!NOTE]
> <P>Conflicts in loyalty scheme ID numbers are resolved automatically by the upgrade process. Scheme IDs that are renamed by the upgrade process can’t be renamed after the process is completed.</P>



1.  Click **Retail** \> **Setup** \> **Loyalty** \> **Resolve conflict cards**.

2.  In the **Resolve conflict cards** form, in the **New card number** field, enter the new card number for each loyalty card in the list.
    
    You can use the existing card number for one card. For example, you have two cards numbered **Card1**. One is assigned to company **CEU**, and one is assigned to company **CEE**. For the card that is assigned to company **CEU**, enter **Card1** in the **New card number** field. For the card that is assigned to company **CEE**, enter **Card2**.

3.  Select the rows that are ready to be migrated, and click **Migrate**. If any card conflicts are not resolved for selected rows, no selected rows will be migrated. Resolve all card conflicts for the selected rows and then click **Migrate** again.

4.  After the migration process is completed, the **IsMIgrated** check box will be selected for all loyalty card rows that have been migrated. You can view the migrated loyalty card numbers in the **Loyalty cards** form.

Loyalty card and transaction data is migrated from the **RetailLoyaltyMSRCardTable** to the **RetailLoyaltyCard** table. For loyalty cards that have conflicts, after you resolve the conflicts and click the **Migrate** button, the loyalty card data is migrated from the **RetailLoyaltyConflictCard** table to the **RetailLoyaltyCard** table. Loyalty card transactions are migrated from the **RetailLoyaltyConflictCardPointTrans** table to the **RetailLoyaltyCardRewardPointTrans** table.

  


