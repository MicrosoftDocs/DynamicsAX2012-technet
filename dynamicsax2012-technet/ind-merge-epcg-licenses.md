---
title: (IND) Merge EPCG licenses
TOCTitle: (IND) Merge EPCG licenses
ms:assetid: 14720789-b60e-49db-a263-d16ef2bba40d
ms:mtpsurl: https://technet.microsoft.com/library/JJ664506(v=AX.60)
ms:contentKeyID: 49385585
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- merge
- (IND)
- india
- EPCG licenses
- Merge EPCG licenses
audience: Application User
ms.search.region: India
---

# (IND) Merge EPCG licenses 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can merge two or more Export Promotion Capital Goods (EPCG) licenses into a single license. After you merge the licenses in Microsoft Dynamics AX, you can apply to the Directorate General of Foreign Trade (DGFT) for approval to merge the licenses.

In Microsoft Dynamics AX, you can merge EPCG licenses only if the following conditions are true:

  - The issue dates of the selected licenses fall within the same fiscal period.

  - The status of all the selected licenses is **Approved**.

  - The port ID is the same for all the selected licenses.

  - The status of the selected licenses is either **Original** or **Domestic**. You cannot merge a combination of original and domestic licenses.

<!-- end list -->

1.  Click **General ledger** \> **Common** \> **EXIM EPCG Schemes**. In the **EXIM EPCG Schemes** list, select the EPCG schemes to merge. All of the selected licenses must have a status of **Approved**.

2.  In the **EXIM EPCG Schemes** form, on the **Overview** FastTab, click **Functions** \> **Merge**.

3.  In the **Merge EPCG licenses** form, click the **Authorization information** FastTab. Then, in the **Approval details** field group, in the **Merge license to** field, select the authorization ID for the EPCG license to merge the selected licenses with. Click **Select**.

4.  Click **Export obligation period**. In the **Create export obligation periods** form, set up export obligation periods for the merged EPCG license, and then close the form.

In the **EXIM EPCG Schemes** form, the merged schemes are updated to include the following information:

1.  On the **Overview** FastTab, the licenses that you merged have a status of **Merged**, and the **Close** check box is selected for the merged licenses.

2.  The new merged license has a status of **Approved**.

3.  The authorization basis and port ID of the merged license are displayed.

4.  On the **Lines** FastTab, the license number that was issued by the DGFT for the merged license is displayed.

## See also

[(IND) Merge EPCG licenses (form)](https://technet.microsoft.com/library/jj678008\(v=ax.60\))

[(IND) Approve an EPCG license](ind-approve-an-epcg-license.md)

[(IND) Verify the approved EPCG scheme details](ind-verify-the-approved-epcg-scheme-details.md)

  


