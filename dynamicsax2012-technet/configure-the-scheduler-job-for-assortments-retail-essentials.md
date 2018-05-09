---
title: Configure the scheduler job for assortments (Retail essentials)
TOCTitle: Configure the scheduler job for assortments (Retail essentials)
ms:assetid: 366220ae-1476-4bef-bd1f-7c46bda57d33
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn716070(v=AX.60)
ms:contentKeyID: 62200331
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Configure the scheduler job for assortments (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to configure the scheduler job that sends product assortments to retail stores. The scheduler job for assortments is automatically run when an assortment is published.

You should also set up the assortments scheduler to run periodically as a batch job. The batch job will update any assortments when new products are added to categories that are assigned to the assortments. This batch job also automatically assigns the assortments that are assigned to a store group to any new retail stores that are added to the store group.

1.  Click **Retail essentials** \> **Data synchronization** \> **Process assortments**.

2.  In the **Retail assortments job** form, on the **Batch** tab, select the **Batch processing** check box.

3.  If you want to run the batch process as part of a group of jobs, select a batch group in the **Batch group** field.

4.  Click **Recurrence**.

5.  In the **Recurrence** form, specify how frequently this job runs. Set the frequency based on how frequently the assortments or the retail stores that the assortments are assigned to change.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Assortments (Retail essentials)](assortments-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

