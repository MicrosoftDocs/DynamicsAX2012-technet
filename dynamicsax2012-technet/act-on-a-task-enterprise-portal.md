---
title: Act on a task (Enterprise Portal)
TOCTitle: Act on a task
ms:assetid: 0b6d7bdf-e338-4d96-9ab1-1ab4cc74feb8
ms:mtpsurl: https://technet.microsoft.com/library/Hh271450(v=AX.60)
ms:contentKeyID: 36384082
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Act on a task (Enterprise Portal) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A task is a unit of work that is associated with a specific business document. For example, a purchase requisition workflow might have a task that requires that you:

  - Add a vendor to each line item on the purchase requisition.

  - Call the vendors listed on the purchase requisition.

To act on a task that is assigned to you, follow these steps:

1.  View the document that has the task associated with it.
    

    > [!NOTE]
    > <P>If your organization uses Role Centers, you can use the <STRONG>Work list</STRONG> Web part to view the tasks assigned to you. For more information, see <A href="view-your-work-items-enterprise-portal.md">View your work items (Enterprise Portal)</A>.</P>



2.  Review the workflow message bar for information about the task. Click the icon on the message bar to view detailed instructions about the task.

3.  A task can be assigned to multiple people; however, only one person can complete the task. If this task is assigned to multiple people, but you want to complete it, click **Actions** \> **Accept**. This indicates that you will complete the task.

4.  Click **Actions** and then click one of the following options.
    

    > [!NOTE]
    > <P>The options that you see may vary, depending on how this task was configured.</P>

    
      - **Complete** – You have completed the task.
    
      - **Reject** – Reject the document. The workflow process will end. However, the originator can resubmit the document, with or without changes.
    
      - **Request change** – Request changes to the document.
    
      - **Delegate** – Reassign the task to another user.
    
      - **Reassign** – Reassign the task to another work item queue.
    
      - **Release** – You cannot complete the task. The document will be reassigned back to the work item queue so that another user can complete it.
    
      - **View history** – View the workflow status and history of the document.

  


