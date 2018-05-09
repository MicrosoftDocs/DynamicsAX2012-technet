---
title: Set up financial journal approvals
TOCTitle: Set up financial journal approvals
ms:assetid: 02c774ac-db76-4709-98a4-c1a14db1948a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230652(v=AX.60)
ms:contentKeyID: 36055934
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up financial journal approvals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some organizations require that journals be approved by a user other than the user who entered the journal. Two types of approvals are available for financial journals: manual and workflow. Based on journal names, you can require manual approval, workflow approval, or no approval. You cannot use both the manual approval system and the workflow approval system for the same journal name.

If manual journal approval is required, a user who enters transactions in a journal reports the journal as ready. An authorized user must approve the journal in the relevant **Journal** form before the journal can be posted. For more information, see [Approve a journal](approve-a-journal.md).

If workflow journal approval is enabled, the user who enters transactions in a journal submits the journal to workflow for approval. Workflow creates the appropriate approvals, tasks, and user-specified notifications, and assigns them to the appropriate users and roles as identified in the workflow. The financial journal approval workflows automate the approval process and allow users who have approval rights to approve from an approval task without directly accessing the journal. For more information, see [Submit a document](submit-a-document.md) and [Review a document assigned to you for approval](review-a-document-assigned-to-you-for-approval.md).

Some buttons in the **Journal** and **Journal voucher** forms are not available when a journal has been submitted for workflow journal approval. When the journal is approved, the options under the **Post** button are available and the other controls and fields in the form are not available. If a user edits one or more lines in an approved journal, the workflow status is reset, the options under the **Post** button are not available, and the other controls and fields are available. When the changes have been made, the journal must be resubmitted for approval.

## Set up manual journal approval

The user who is responsible for journal routines sets up the approval system for each journal where approvals will be used. Manual journal approval is available for all journals in Microsoft Dynamics AX.

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  In the left pane, select the journal to use the approval system for; for example, a journal that has a journal type of **Daily**.

3.  In the **Approval** field group, select the **Active** check box, and then select a user group in the **Approve** field. The users who belong to this user group will be able to manually approve these journals.

## Set up workflow journal approval

The user who is responsible for journal routines sets up the approval system for each journal where approvals will be used. Workflow journal approval is available only for selected financial journals. Before you begin, make sure that workflows have been set up for the journal types that you will use workflow approval for. For more information, see [Set up Accounts payable workflows](set-up-accounts-payable-workflows.md), [Set up Accounts receivable workflows](set-up-accounts-receivable-workflows.md), [Set up Fixed assets workflows](set-up-fixed-assets-workflows.md), and [Set up General ledger workflows](set-up-general-ledger-workflows.md).

1.  Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**.

2.  In the left pane, select the journal to use the approval system for; for example, a journal that has a journal type of **Daily**.

3.  In the **Approval workflow** field group, select the **Approval workflow** check box, and then select a workflow that has been set up for the journal type in the **Workflow** field.

## See also

[Overview of the workflow system](overview-of-the-workflow-system.md)

[Workflow concepts](workflow-concepts.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

