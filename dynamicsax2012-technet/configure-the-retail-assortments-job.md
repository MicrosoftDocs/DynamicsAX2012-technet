---
title: Configure the retail assortments job
TOCTitle: Configure the retail assortments job
ms:assetid: 8691dc3a-483c-43aa-91c1-f96500314cdb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh597159(v=AX.60)
ms:contentKeyID: 39519216
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure the retail assortments job [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

The assortments scheduler is automatically run when an assortment is published. You should also set up the assortments scheduler to run periodically as a batch job. The assortment scheduler batch job will update any assortments when new products are added to categories that are assigned to the assortments. This batch job also automatically assigns the assortments that are assigned to a store group to any new retail channels that are added to the store group.

1.  Click **Retail** \> **Periodic** \> **Process assortments**.

2.  In the **Retail assortments job** form, on the **Batch** tab, select the **Batch processing** check box.

3.  If you want to run the batch process as part of a group of jobs, select a batch group in the **Batch group** field.

4.  Click **Recurrence**.

5.  In the **Recurrence** form, set the parameters to specify how frequently this job runs. Set the frequency based on how frequently the assortments or the retail channels that the assortments are assigned to change.

## See also

[Retail assortments job (form)](https://technet.microsoft.com/en-us/library/hh597306\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

