---
title: Delete project journals
TOCTitle: Delete project journals
ms:assetid: b1c9c606-9c92-41e6-aeb7-29d6065c4feb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh781098(v=AX.60)
ms:contentKeyID: 43894511
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- outstanding transactions
---

# Delete project journals [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can delete project journals from which transactions have been posted. By deleting these project journals, you can help make more system resources available. Use the following procedures to delete project journals.


> [!NOTE]
> <P>You can delete journals only for hours and fees.</P>



## Delete a specific project journal

1.  Click **Project management and accounting** \> **Periodic** \> **Journals** \> **Delete project journals**.

2.  In the **Delete project journals** form, click **Select**.

3.  In the **ProjJournalCleanUp** form, in the **Criteria** field, select the journal that you want to delete.

4.  Click **OK**.

## Delete multiple project journals

1.  Click **Project management and accounting** \> **Periodic** \> **Journals** \> **Delete project journals**.

2.  In the **Delete project journals** form, click **Select**.

3.  In the **ProjJournalCleanUp** form, in the **Criteria** field, select a journal to delete.

4.  Click **Add**, and then select another journal to delete.

5.  Repeat step 4 for each journal that you want to delete.

6.  Click **OK**.


> [!NOTE]
> <P>You can also create a batch job to delete multiple journals. For more information about batch jobs, see <A href="submit-a-batch-processing-job-from-a-form.md">Submit a batch processing job from a form</A>.</P>



## Delete all hour journals

1.  Click **Project management and accounting** \> **Periodic** \> **Journals** \> **Delete project journals**.

2.  On the **General** tab, select the **Hour** check box, and then click **OK**.


> [!WARNING]
> <P>This procedure deletes all hour journals.</P>



## Delete all fee journals

1.  Click **Project management and accounting** \> **Periodic** \> **Journals** \> **Delete project journals**.

2.  On the **General** tab, select the **Fee** check box, and then click **OK**.


> [!WARNING]
> <P>This procedure deletes all fee journals.</P>



## See also

[Delete project journals (class form)](https://technet.microsoft.com/en-us/library/aa619118\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

