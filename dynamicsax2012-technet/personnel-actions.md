---
title: Personnel actions
TOCTitle: Personnel actions
ms:assetid: 98a3ea89-d4b0-4e5e-874a-a734081dfa7d
ms:mtpsurl: https://technet.microsoft.com/library/Dn527696(v=AX.60)
ms:contentKeyID: 59626234
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- status
- personnel actions
- PAF
- Forms.HcmPositionActionList
- failed action
- Forms.HcmWorkerActionDetail
- PAR
- Forms.HcmWorkerActionList
- MsDynAx060.Forms.HcmPositionActionList
- MsDynAx060.Forms.HcmWorkerActionDetail
- MsDynAx060.Forms.HcmWorkerActionList
- personnel action
audience: Application User
ms.search.region: Global
---

# Personnel actions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic contains answers to questions that you might have if your organization uses personnel actions. Personnel actions are additional steps that you must complete when you perform certain personnel-related tasks. Examples of tasks that might require personnel actions are when you create new positions, modify existing position values, hire new workers, transfer workers, change worker compensation, change position assignments, or terminate workers.


> [!NOTE]
> <P>Personnel actions are available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the <STRONG>Personnel actions</STRONG> configuration key is selected.</P>



## How can I tell if my organization requires personnel actions?

Personnel actions are required by your organization if you are asked to select a personnel action when you create new positions, change existing positions, hire new workers, transfer workers, change worker compensation, change position assignments, terminate workers, or enter leave for workers.

You can also click **Human resources** \> **Common** \> **Actions**. If you don’t see an **Actions** option, your organization doesn’t use personnel actions.

## What is the difference between a position action and a worker action?

There are two types of personnel actions:

  - **Position action** – A position action is performed on existing positions or new positions. For example, a position action might be required if you change a value on an existing position or if you create a new seasonal position. For detailed information about how to use position actions, see [Key tasks: Existing worker positions](key-tasks-existing-worker-positions.md) or [Key tasks: New worker positions](key-tasks-new-worker-positions.md).

  - **Worker action** – A worker action is performed on existing employees or new employees. For example, a worker action might be required when a new employee is hired or an existing employee is promoted. For detailed information about how to use worker actions, see [Assign personnel actions to workers](https://technet.microsoft.com/library/dn479033\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Worker actions are available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the <STRONG>Personnel actions</STRONG> configuration key is selected.</P>



## Can I view a list of all my personnel actions?

No, you can’t view a list of all your personnel actions. However, you can use the **Actions** list pages to view all your position actions or all your worker actions. You can also view worker actions that have a specific status. Click **Human resources** \> **Common** \> **Actions** to access the following personnel action list pages:

  - **Position actions** – View a list of all pending and completed position actions.

  - **All worker actions** – View a list of all pending and completed worker actions.

  - **Pending worker actions** – View a list of worker actions that don’t have a status of **Completed** or **Denied**.

  - **Completed worker actions** – View a list of worker actions that have a status of **Completed** or **Denied**.
    

    > [!NOTE]
    > <P>Worker actions are available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed and the <STRONG>Personnel actions</STRONG> configuration key is selected.</P>



## What do the statuses of the personnel actions mean?

Personnel actions can have one of the following statuses:

  - **Draft** – If workflow is used, the action hasn’t been submitted. If workflow isn’t used, the action hasn’t been completed.

  - **In review** – The personnel action has been submitted to workflow, but the workflow is not completed.

  - **Approved waiting** – The workflow is completed, but the changes are still in process.

  - **Canceled** – The workflow was canceled or the personnel action was recalled.

  - **Rejected** – The action request was rejected by the approver.

  - **Processing action** – The action request has been approved and the changes are being processed.

  - **Workflow complete** – The workflow is completed and the changes have been processed.

  - **Failed** – The workflow failed because the information is out of date. Click **Reactivate** to display the latest information and continue.

  - **Completed** – The position was successfully created or modified, or the employee was successfully hired, transferred, or terminated, or had their compensation changed.

  - **Error** – A problem occurred other than information being out of date. Open the **Personnel actions message log** to determine the cause of the error.

  - **Denied** – The action request was denied by the approver.

## Can I delete a personnel action?

Yes, you can delete personnel actions that have a status of **Draft**, **Error**, **Failed**, or **Canceled**.

## What is the fastest way to tell if there are attachments assigned to a personnel action?

Open any of the personnel action list pages and select a personnel action. The **Related information** section in the FactBox displays the number of attachments that are assigned to it.


> [!TIP]
> <P>Click <STRONG>Attachments</STRONG> on the Action Pane to view the attachments. All the attachments are displayed. These include notes and website links. To add an attachment, click <STRONG>New</STRONG>.</P>



## What is the fastest way to check the status of a personnel action request?

Open any of the personnel action list pages and select a personnel action. The status appears in the **Review process details** FactBox.

## What should I do if a personnel action request fails?

If a personnel action request fails, follow these steps to resolve the error and resubmit the request:

1.  On the **Action Pane**, click the **Error text** button to view the message text that describes the problem.

2.  On the **Action Pane**, click **Reactivate** to load the latest information and set the status of the personnel action back to **Draft**.

3.  Resolve the error, and then click **Complete** or **Submit**.
    

    > [!TIP]
    > <P>If you received an error message that says a worker already exists, but you want to add the new worker anyway, you can open the personnel action and clear the <STRONG>Check for duplicates</STRONG> box on the <STRONG>Action</STRONG> tab to resolve the error.</P>



## What happens to a personnel action that uses workflow when the final approval is completed?

If there are no errors, the personnel action becomes read-only. (You can view the history on the **All worker actions** list page, but you can’t change the personnel action.) When the status of a personnel action is **Completed**, the position or worker record has already been updated. To view the changes that were performed, open the **Positions** or **Workers** list page.

## Why do I get this error when I click Submit or Complete? “The Plan field in the Compensation fast tab is required because a fixed compensation action is assigned. Click Reactivate and then clear both fields if you do not want to enter compensation.”

This message is displayed when a fixed compensation action is assigned and a plan is also required. Your system administrator has mapped a fixed compensation action to the personnel action that you selected. This saves you time when you enter data because these fields are typically very similar. When a fixed compensation action is assigned, the **Plan** field is required, which is why you receive this error message.

To resolve this error, follow these steps:

1.  On the **Compensation** tab, select a plan.

2.  If you don’t want to assign compensation yet, select the value in the **Fixed compensation action** field and delete it.


> [!TIP]
> <P>If you find that you’re clearing this field too often, you can ask your system administrator to remove the association in the <STRONG>Personnel action types</STRONG> form. Alternatively, the system administrator can create a new personnel action type that has the <STRONG>Fixed compensation action</STRONG> field cleared in the <STRONG>Personnel action types</STRONG> form.</P>



## Why do I receive the following error when I enter a non-zero value in the Pay rate field? “The value is out of its valid range - it must be between 0.00 and 0.00”

You receive this message because the **Level** field in the **Job** form is blank for the job that is associated with the selected position.

To resolve this error, follow these steps:

1.  On the **Worker position assignments** tab, right-click in the **Position** field and select **View details**.

2.  Click the **Job** field value (the link) to open the **Job** form.

3.  On the **Action Pane**, click **Edit**.

4.  Click the **Compensation** tab.

5.  In the **Level** field, select a level.

6.  Close the **Job** form.

7.  Close the **Position** form.

8.  Return to the **Compensation** tab on the **Worker** form, select a value in the **Plan** field, and then enter the employee’s compensation in the **Pay rate** field.

## Why can’t I change the effective date in the header of the Worker action form?

You can’t change the effective date because the field is populated with the most logical date for the action type.

For example:

  - The effective date in the header of a **Terminate a worker** action is the date that you entered in the **Termination date** field.

  - The effective date of a **Hire a worker** action is the date that you entered in the **Employment start date** field.

  - The effective date of a **Transfer a worker** action is the date that you entered in the **Assignment start date/time** field for the worker.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


