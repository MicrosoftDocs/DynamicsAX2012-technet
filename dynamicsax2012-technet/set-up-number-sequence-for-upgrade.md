---
title: Set up number sequence for upgrade
TOCTitle: Set up number sequence for upgrade
ms:assetid: 98efee6f-bb16-4850-9ccb-8ab0fc6f9398
ms:mtpsurl: https://technet.microsoft.com/library/Gg731876(v=AX.60)
ms:contentKeyID: 35132778
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- set up number sequence for upgrade
---

# Set up number sequence for upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In releases before Microsoft Dynamics AX 2012, the general ledger was always related to a single voucher, regardless of the source document. Now that some subledger journal entries can be summarized when they are transferred to the general ledger, a new numbering sequence is needed for the general journal entries.

Use the **Set up number sequence for upgrade** form to set up the number sequence code for the legal entities.

1.  Click **Set up number sequence for upgrade** in the **Preprocessing upgrade checklist** to open the **Set up number sequence for upgrade** form.

2.  In the **Company accounts** field, select the set of legal entity accounts to upgrade the number sequence for.

3.  Click **Set up number sequence** to open the **Set up number sequence** form, where you can select the number sequence code to use for the general journals, purchase agreements, and sales agreements.
    

    > [!WARNING]
    > <P>To avoid performance and data issues, we strongly recommend that you right-click in the <STRONG>Number sequence</STRONG> field and select <STRONG>View details</STRONG> to set up a new, continuous number sequence for each number sequence module.</P>

    
    To avoid overlapping agreement numbers, you must select different number sequence codes for purchase agreements and sales agreements.

4.  To use the same number sequence code for all sets of legal entity accounts, click **Apply to remaining companies**. Otherwise, repeat steps 2 and 3 until you have selected a number sequence code for all sets of legal entity accounts.

5.  Click **Set to ready for upgrade** to select this checklist item as ready for upgrade.

## See also

[Set up number sequence for upgrade (form)](https://technet.microsoft.com/library/hh202085\(v=ax.60\))

  


