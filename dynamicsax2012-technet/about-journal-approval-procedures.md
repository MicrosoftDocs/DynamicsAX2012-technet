---
title: About journal approval procedures
TOCTitle: About journal approval procedures
ms:assetid: effa7746-7ad0-4033-8d83-3119aef8e785
ms:mtpsurl: https://technet.microsoft.com/library/Aa551570(v=AX.60)
ms:contentKeyID: 37822168
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approval procedure
- approve journal
audience: Application User
ms.search.region: Global
---

# About journal approval procedures 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you define an approval procedure for a journal, journal lines that are entered in the journal cannot be processed until the tasks that require approval have been approved. For example, you can use a journal approval procedure to require that hours that are submitted on timesheets be approved before the related transaction is posted.

Journal approval is an optional feature that can be set up for individual journals. In any given journal, you can specify whether tasks such as posting require approval.

An approval procedure can contain any number of approval steps and any combination of status values. The approval steps define the tasks that might be assigned to a worker who works with project journal entries. These tasks include editing, posting, and checking.

For example, for journals that are used for timesheet postings, you can create three status values: Enter, Approve, and Post. In the **Journal approval setup** form, you can specify that, after a timesheet has been entered and approved through the specified timesheet workflow, the related journal must also be approved before it can be posted.

To apply an approval procedure for hours to a journal, attach the approval procedure to a journal name. A journal name is also referred to as a journal setup. Then, in the **Hour** journal where you want tasks to be approved, select this journal name. The journal approval procedure that is defined in the journal name is then applied to your journal.

The steps can be summarized as follows:

1.  Create an approval procedure.

2.  Create a journal name, or journal setup, and select the approval procedure.

3.  Create an **Hour** journal, and reference the journal name to which the approval procedure has been attached.

In the journal, you can also overwrite the approval procedure that is attached to the journal name. You can then define the journal approval procedure directly in the journal.

## See also

[Create a journal approval procedure](create-a-journal-approval-procedure.md)

[Set up journal names](set-up-journal-names.md)

[Apply a journal approval procedure](apply-a-journal-approval-procedure.md)

  


