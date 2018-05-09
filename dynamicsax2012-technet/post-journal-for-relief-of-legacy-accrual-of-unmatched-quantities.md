---
title: Post journal for relief of legacy accrual of unmatched quantities
TOCTitle: Post journal for relief of legacy accrual of unmatched quantities
ms:assetid: 01d42503-362a-4a9b-88ca-3f3325714991
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751341(v=AX.60)
ms:contentKeyID: 35132525
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Post journal for relief of legacy accrual of unmatched quantities 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to post a journal that relieves any legacy accrual accounting entries that still remain for unmatched quantities. Unmatched quantities are quantities of purchased products that are received but not yet invoiced. Select the journal name that you have defined during the pre-processing upgrade. After you select the name, post the journal.

### Post the journal

1.  Check that the journal name is correctly displayed in the **Task description** field, and then click **OK** to post the journal. To set up a batch job to post the journal, select a batch group to associate the journal with in the **Batch group** field and then follow the rest of this procedure.

2.  Click **Private** if you want to make sure that only the user who set up the batch job can run it.

3.  Click **Batch processing** if you want to run the task as a batch job.

4.  Click **Recurrence** and **Alerts** to define the frequency of the batch job, and whether any alerts should be defined for the job.

5.  Click **OK** to post the journal or start the batch job.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

