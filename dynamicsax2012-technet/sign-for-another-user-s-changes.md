---
title: Sign for another user's changes
TOCTitle: Sign for another user's changes
ms:assetid: cb63ead7-c40f-4a4c-a9f8-2f7afefe787e
ms:mtpsurl: https://technet.microsoft.com/library/Dd362077(v=AX.60)
ms:contentKeyID: 36059342
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- compliance
- e-signature
audience: Application User
ms.search.region: Global
---

# Sign for another user's changes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

At times, you might want a user to sign for another user's changes. For example, a supervisor might be required to sign for changes that an employee makes to a bill of materials. Use this procedure to designate a Microsoft Dynamics AX user as a signer for another user.


> [!NOTE]
> <P>When a user signs for another user's change, the signature must be provided at the workstation of the user who made the change. The user cannot save the change until the signature has been provided.</P>



1.  Click **File** \> **Tools** \> **Options...**. In the **Miscellaneous** FastTab, click **Electronic signature** \> **Designate approver**.

2.  Press CTRL+N to create a new record.

3.  In the **Approver user ID** field, select the ID of the user who must sign for another user's changes.

4.  In the **Sign for user ID** field, select the ID of the user whose changes must be signed for.

5.  To designate additional approvers, press CTRL+N to create a new record.

6.  Close the forms to save your changes.

  


