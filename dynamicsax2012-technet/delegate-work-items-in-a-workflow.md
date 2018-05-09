---
title: Delegate work items in a workflow
TOCTitle: Delegate work items in a workflow
ms:assetid: b94a479d-9d4b-4815-862b-64869d87f46d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213581(v=AX.60)
ms:contentKeyID: 35949351
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Delegate work items in a workflow 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you plan to be out of the office or otherwise unavailable to act on work items, you can delegate, or reassign, your work items to other users.

You can configure the system to automatically delegate your work items, or you can manually delegate a specific work item to another user.

## Set up automatic delegation

To configure the system to automatically delegate your work items to other users, you must create delegation rules, which specify when certain types of work items are delegated. Follow these steps to create a delegation rule.

1.  Click **File** \> **Tools** \> **Options**.

2.  In the left pane, click **Delegation**.

3.  Click **Add** to create a delegation rule.

4.  In the **Scope** field, select one of the following options:
    
      - **All** – Delegate all work items that are assigned to you.
    
      - **Module** – Delegate only the work items that are related to a specific type of workflow. If you select this option, you must select the type of workflow in the **Name** field.
    
      - **Workflow** – Delegate only the work items that are related to a specific workflow. If you select this option, you must select the workflow in the **Name** field.

5.  In the **Delegate** field, select the user to delegate the work items to.

6.  Use the **Start date/time** and **End date/time** fields to specify when you want the work items to be automatically delegated.

7.  Select the **Enabled** check box to activate the delegation rule.

8.  In the **Comment** field, enter a comment that explains why you are delegating the work items.

## Manually delegate a specific work item

Follow these steps to manually delegate a work item when you are viewing a document.

1.  Open the document that you have been assigned a work item for.

2.  On the workflow message bar, click **Actions** \> **Delegate**. A dialog box appears.

3.  Select the user to delegate the work item to.

4.  Enter a comment that explains why you are delegating the work item.

5.  Click **Delegate**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

