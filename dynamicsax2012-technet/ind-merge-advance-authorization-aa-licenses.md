---
title: (IND) Merge Advance authorization (AA) licenses
TOCTitle: (IND) Merge Advance authorization (AA) licenses
ms:assetid: 489e95b5-79e5-4db7-b04b-32d5800e462c
ms:mtpsurl: https://technet.microsoft.com/library/JJ664668(v=AX.60)
ms:contentKeyID: 49385742
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- merge
- (IND)
- india
- AA
- Advanced Authorization
- merge AA
audience: Application User
ms.search.region: India
---

# (IND) Merge Advance authorization (AA) licenses 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can merge export-import (EXIM) Advance Authorization (AA) incentive schemes and common processes that are related to the incentive schemes under the following conditions:

  - The status of the AA schemes is set to **Approved**.

  - The product group and port ID that are assigned to the selected AA schemes are the same.

  - The license status of the selected transaction lines is **Original**.

  - The import expiration date of the selected transaction lines is still valid.

After you merge the selected AA schemes, you can apply to the customs authority to approve the new merged AA license. After the customs authority approves the merge, you can export and import materials based on the new authorization.

When multiple authorizations are merged, the following actions occur:

  - The import and export expiration dates of the most recent authorization are used as the import and export expiration dates of the merged authorization.

  - The status of the merged AA schemes is updated to **Merged**.

  - In the **EXIM Authorization schemes** form, the **Close** check box is selected for the AA schemes that were merged.

  - A new AA scheme is created for the merged AA schemes. The new AA scheme has a status of **Approved**.
    

    > [!NOTE]
    > <P>You can also merge multiple AA schemes into an existing AA scheme that you select, instead of creating a new AA scheme.</P>



<!-- end list -->

1.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. On the **EXIM Authorization schemes** list page, in the filter area, in the **Authorization type** field, select **AA**.

2.  In the list, select the AA license to merge. Then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

3.  In the **EXIM Authorization schemes** form, select at least two AA licenses. On the **Overview** FastTab, click **Functions**, and then click **Merge**.

4.  In the **Merge licenses** form, in the **Merge to Authorization ID** field, select the primary AA license that the other selected authorization licenses are being merged with. All the authorizations that you selected in the **EXIM Authorization schemes** form are available for selection. Then click **Select**.
    
    The **Authorization number**, **Import expiration date**, and **Export expiration date** fields are updated for the selected authorization. You can change the import and export expiration dates.

5.  In the **Reference number** field, enter the new reference number that the customs authority issued for the merged license.

6.  In the **Reference date/time** field, enter the date on which the customs authority issued the merged license.

7.  In the **Reason** field, enter information about the merge.

8.  Click **OK**. When a message prompts you to confirm that you want to continue the merge, click **Yes**.

## See also

[(IND) Merge licenses (form)](https://technet.microsoft.com/library/jj677912\(v=ax.60\))

[(IND) Create an export order and apply the AA incentive scheme to the export order](ind-create-an-export-order-and-apply-the-aa-incentive-scheme-to-the-export-order.md)

[(IND) Create an import order and apply the AA incentive scheme to the import order](ind-create-an-import-order-and-apply-the-aa-incentive-scheme-to-the-import-order.md)

  


