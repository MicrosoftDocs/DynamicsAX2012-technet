---
title: (LTU) Change the fixed asset group for a fixed asset
TOCTitle: (LTU) Change the fixed asset group for a fixed asset
ms:assetid: 6d31f49c-d20b-4792-b57f-a9f2cdbf7cc5
ms:mtpsurl: https://technet.microsoft.com/library/JJ665108(v=AX.60)
ms:contentKeyID: 49386690
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed asset group
- change fixed asset
- change group
- change the fixed asset group
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Change the fixed asset group for a fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

All fixed assets are assigned to a fixed asset group. In some situations, a fixed asset must be moved from the original fixed asset group to another one. Use this procedure to change the fixed asset group for a fixed asset.

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset, and then, on the **Action Pane**, in the **Maintain** group, click **Change fixed asset group**.

3.  In the **Change fixed asset group** form, in the **Fixed asset group** field, select the fixed asset group to which to move the fixed asset.

4.  To assign a new number to the fixed asset, select the **New fixed asset number** check box.
    
    The **Fixed asset number** field displays the new fixed asset number.

5.  In the **Date** field, select the ledger posting date for the fixed asset.

6.  In the **Journal** field, select the journal to which to post the fixed asset.

7.  Click **OK** to transfer the fixed asset.

8.  When the **Rename?** question appears, click **Yes** to confirm the transfer and generate the transfer journal.

9.  In the Infolog, note the number of the journal that the process generated, and then close the Infolog.
    

    > [!IMPORTANT]
    > <P>You must post the transfer journal to complete the transfer process.</P>



10. Click **Fixed assets** \> **Journals** \> **Fixed assets**.

11. Select the transfer journal, and then click **Post** \> **Post**.

## See also

[(LTU) Create a transfer packing slip for a fixed asset](ltu-create-a-transfer-packing-slip-for-a-fixed-asset.md)

  


