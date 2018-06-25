---
title: About advanced ledger entry workflows (Public sector)
TOCTitle: About advanced ledger entry workflows (Public sector)
ms:assetid: 0941a884-764c-4e4c-832a-af33a47622ca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208501(v=AX.60)
ms:contentKeyID: 36056239
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- workflows
- advanced ledger entry workflows
- workflows advanced ledger entry
---

# About advanced ledger entry workflows (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some public sector organizations require that advanced ledger entries be approved by a user other than the person who originated the entry. You can require workflow approval by setting up and activating a workflow configuration for advanced ledger entries. You can set up a workflow to require that all advanced ledger entries be submitted for approval, or only those that meet specified conditions.


> [!NOTE]
> <P>If you do not want any advanced ledger entries to be submitted for review, do not set up a workflow for advanced ledger entries.</P>



The following example illustrates how a workflow might be configured for an organization that requires advanced ledger entry approvals.

Before you complete the procedures in this topic, you should be familiar with the general workflow functionality. For more information, see [Workflow for Microsoft Dynamics AX](workflow-for-microsoft-dynamics-ax.md).

## Example: Configure a workflow where an advanced ledger entry must be approved by a user

A workflow configuration is based on a workflow type. You can create multiple workflow configurations for the advanced ledger entry workflow type. This example explains how to create a simple approval workflow in which you are the user who approves all advanced ledger entries.

1.  Click **General ledger** \> **Setup** \> **General ledger workflows**.

2.  On the **Action Pane**, click **New**.

3.  Select **Advanced ledger entry workflow** and then click **Create workflow**.

4.  On the **Action Pane**, click **Properties**. Enter a name for the workflow and submission instructions. Then click **Close**. For more information, see [Configure the properties of a workflow](configure-the-properties-of-a-workflow.md).

5.  Drag the **Advanced ledger entry approval** element onto the flowchart canvas. Use the connection points to define an incoming sequence flow from the green **Start** element and an outgoing sequence flow to the red **Stop** element. This is easier to do if you drag the **Stop** element close to the **Start** element before you drag the **Advanced ledger entry approval** element onto the canvas. For more information, see [Create a workflow](create-a-workflow.md).
    

    > [!NOTE]
    > <P>There are standard flow controls that you can use to create more complex workflows. For example, you could create a conditional workflow where one user approves advanced ledger entries for high amounts and another user approves advanced ledger entries for lower amounts. There is also a task element that you can use if you want a user to verify the fields on an advanced ledger entry.</P>



6.  Right-click the **Advanced ledger entry approval** element and select **Properties** where you can enter a name for the approval element. Then click **Close**. For more information, see [Configure an approval process](configure-an-approval-process.md).

7.  Double-click the approval element and right-click the step element. Select **Properties** to open the approval step properties. For more information, see [Configure an approval step](configure-an-approval-step.md).

8.  In the **Basic Settings** text boxes, enter a name, subject, and instructions for the approval step.

9.  Click **Assignment** to assign a user to the approval step. To assign yourself as the approver, do the following:
    
    1.  From the **Assign users to this workflow element** list on the **Person** tab, click **User**.
    
    2.  On the **User** tab, move your user ID from **Available users:** to **Selected users:**.
    
    3.  Click **Close**.

10. Click **Save and close**, enter version notes, and then click **OK**.

11. Select **Activate the new version** and then click **OK.**

## See also

[Advanced ledger entry (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208579\(v=ax.60\))

[Set up General ledger workflows](set-up-general-ledger-workflows.md)

[About free text invoice workflows](about-free-text-invoice-workflows.md)

[Workflow for Microsoft Dynamics AX](workflow-for-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

