---
title: Configure personnel actions
TOCTitle: Configure personnel actions
ms:assetid: 5722ce62-09ce-48e6-8100-5eaba0aeb9d1
ms:mtpsurl: https://technet.microsoft.com/library/Dn527694(v=AX.60)
ms:contentKeyID: 59626227
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- raise
- personnel actions
- Forms.HcmActionTypeSetup
- personnel
- compensation change
- merit decrease
- personnel action form
- PAF
- personnel action request
- leave of absence
- merit increase
- salary change
- MsDynAx060.Forms.HcmActionTypeSetup
- personnel action
- raises
audience: Application User
ms.search.region: Global
---

# Configure personnel actions 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic is intended for system administrators and describes how to set up personnel actions. Personnel actions are optional. If you enable personnel actions, you can require users to enter additional information when they perform the following tasks:

  - Create new positions

  - Edit existing position values

  - Hire new workers

  - Transfer workers

  - Terminate workers

If you enable personnel actions, you can also implement an approval or notification process when these tasks are performed.

## Decide whether to enable personnel actions

If you enable personnel actions, users must complete a few extra steps each time they perform the specified tasks. However, the information that users provide in these steps is often invaluable to organizations. Consider the following questions when you decide whether to enable personnel actions.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Question</p></th>
<th><p>Examples</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Does your organization want to collect additional information when users perform personnel actions?</p></td>
<td><p>Users must select a description of why they are changing an existing position or terminating a worker. The descriptions are in a list that you provide.</p>
<p>Users must select a description of why they are transferring a worker. The descriptions are in a list that you provide.</p></td>
</tr>
<tr class="even">
<td><p>Does your organization require an approval or notification process when personnel actions are performed?</p></td>
<td><p>A manager must approve an employee termination and payroll must be notified immediately.</p>
<p>A manager must approve all new positions and the human resources department must be notified of the approval immediately so that they can begin recruiting.</p></td>
</tr>
</tbody>
</table>


If you answered “Yes” to either of those questions, or you need to implement these processes for other personnel actions, your organization should enable personnel actions.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Plan</p></td>
<td><p>Identify all the preferred names and descriptions for personnel action types and determine whether to use workflow, reason codes, and number sequences.</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>Set up a test environment for a week or two so that you know what you want to enter in the live environment.</p></td>
</tr>
<tr class="odd">
<td><p>Release</p></td>
<td><p>Enable the <strong>Personnel actions</strong> configuration key in your live environment, and then close and reopen Microsoft Dynamics AX so that you can access the personnel action forms to set up personnel actions. For more information, see <a href="personnel-actions-configuration-key-hcmpersonnelactions.md">Personnel actions configuration key (HcmPersonnelActions)</a>.</p>
<div class="alert">

> [!WARNING]
> <P>We highly recommend that you make this configuration change during a time of low usage to minimize the impact on your users. If you enable this configuration key but you don’t create personnel action types, users won’t be able to create new positions, edit existing positions, hire new workers, transfer workers, change position assignments, or terminate workers.</P>


</div></td>
</tr>
</tbody>
</table>


## 1\. Optional: Create workflows to assign to personnel action types

You can create a workflow for each personnel action type that requires a review process. We recommend that you create the workflows first, because you assign these to personnel action types when you map them in the next step. You create and maintain workflows on the **Human resource workflows** list page. If you’re not familiar with how to set up workflow, see [Workflow for Microsoft Dynamics AX](workflow-for-microsoft-dynamics-ax.md).

Here are some things to consider when you set up workflow for personnel actions:

  - There are several types of human resource workflows. You have to set up workflows only for the personnel action types that your organization requires.

  - Even if the workflow is the same for two worker action types (for example, the process is the same for new hires and for worker terminations), you have to create two separate workflows – one for each type.

  - You can set up workflows that require approval, that send notifications, or that do both.

The following table lists some examples of when you might or might not use workflows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Workflow</p></th>
<th><p>Examples</p></th>
<th><p>Workflow needed?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Position actions</strong></p></td>
<td><p>Your organization requires management approval when new positions are created. Your organization also wants to notify the Human resources department when the position is approved so that they can begin recruiting.</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Position actions</strong></p></td>
<td><p>Your organization does not require any approvals or notifications when users create new positions or change values on existing positions.</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p><strong>Worker actions hire</strong></p></td>
<td><p>Your organization requires management approval when new employees are hired. Your organization also wants to notify the Payroll department so that they can add the employee to the payroll system.</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p><strong>Worker actions transfer</strong></p></td>
<td><p>Your organization does not require management approval for transferring workers from one position to another, but wants to notify the Payroll department of the change so that they can review the department and region of the new assignment</p></td>
<td><p>Yes</p></td>
</tr>
</tbody>
</table>


## 2\. Create and map personnel action types

When you enable personnel actions, users must select a personnel action type that is specific to your organization when they create new positions, modify existing positions, hire workers, transfer workers, or terminate a worker. You must create a custom personnel action type for each of these personnel actions in order for your users to complete their tasks. One personnel action type is supplied by the system for each of these actions. If your organization uses the same terminology supplied by the system, you can simply type the same name, but if your organization refers to the action differently, or uses more than one description for an action type, you will need to create these custom values.

The following table shows some ways you might map the **Terminate a worker** action, which is provided by the system, to suit your organizational needs.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Personnel action provided by the system</p></th>
<th><p>The custom term that your organization uses to describe this action</p></th>
<th><p>Explanation for the mapping</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Terminate a worker</strong></p></td>
<td><p>“Terminate a worker”</p></td>
<td><p>Your users will understand the system terminology, and you do not have to be more specific, so you use the same name as the system name.</p></td>
</tr>
<tr class="even">
<td><p><strong>Terminate a worker</strong></p></td>
<td><p>“Fire a worker”</p></td>
<td><p>This terminology makes more sense to users, and one action is fine for all terminations.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Terminate a worker</strong></p></td>
<td><p>“Voluntary termination”</p>
<p>&amp;</p>
<p>“Involuntary termination”</p></td>
<td><p>This terminology makes more sense to users, and involuntary terminations require a different workflow than voluntary terminations because the approver is different. You create and map two custom personnel action types to the <strong>Terminate a worker</strong> type provided by the system so that you can assign a different workflow to each one.</p></td>
</tr>
</tbody>
</table>


To create a personnel action type, follow these steps:

1.  Click **Human resources** \> **Setup** \> **Actions** \> **Personnel action types**.

2.  Click **New**.

3.  Enter a custom personnel action type name, such as Edit a position, Seasonal position, Lateral transfer, or those listed in the table earlier in this section.

4.  Enter a detailed description of the action that users can refer to if they need more information to make the appropriate selection.

5.  Select the system action to map the personnel action type to. You must map at least one custom personnel action to each system action that users perform, or they will not be able to complete the task.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Type</p></th>
    <th><p>Available when</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Create positions</strong></p></td>
    <td><p>New positions are created.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Modify positions</strong></p></td>
    <td><p>The values on an existing position are changed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Hire a worker</strong></p></td>
    <td><p>New workers are hired.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transfer a worker</strong></p></td>
    <td><p>Existing workers are assigned to a different position, with or without a change to their fixed compensation plan or pay rate.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Terminate a worker</strong></p></td>
    <td><p>An employee’s employment end date is changed.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>The list earlier in this section includes both worker actions and position actions. If you see only <STRONG>Create positions</STRONG> and <STRONG>Modify positions</STRONG>, you are not using the most current version of Microsoft Dynamics AX. Worker actions are available only if Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2 is installed and the <STRONG>Personnel actions</STRONG> configuration key is selected.</P>



6.  If your organization requires that actions of this type follow a review process, select the workflow ID from the list. You can select only workflows that have a workflow type that corresponds to this personnel action type.

7.  Optional: For **Hire a worker** or **Transfer a worker** personnel action types only, select a fixed compensation action type that corresponds to this personnel action type. This default value is displayed automatically for users so that they don’t have to select a compensation action in addition to the personnel action.
    

    > [!TIP]
    > <P>All users are required to enter a compensation action regardless of whether personnel actions are enabled. When personnel actions are enabled, this requirement often becomes redundant because it is the same information that is supplied for the personnel action request. If this is the case for your organization, selecting a default fixed compensation action type can keep users from having to enter it two times. For more information, see <A href="https://technet.microsoft.com/library/hh694711(v=ax.60)">Fixed compensation actions (form)</A>.</P>



## 3\. Optional: Set up reason codes for personnel actions

When users perform tasks that have personnel actions enabled, they are prompted for a **Reason code**. This reason code provides additional detail about the **Personnel action type** they selected. Some examples are listed in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Personnel action type</strong></p></th>
<th><p><strong>Reason code</strong></p></th>
<th><p><strong>Description</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Voluntary termination</p></td>
<td><ul>
<li><p>Retiring - age</p></li>
<li><p>Retiring – package</p></li>
</ul></td>
<td><ul>
<li><p>Employee has reached retirement age</p></li>
<li><p>Employee has accepted an early retirement package</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>New position</p></td>
<td><ul>
<li><p>Growth</p></li>
<li><p>Seasonal</p></li>
<li><p>Backlog</p></li>
</ul></td>
<td><ul>
<li><p>General expansion of workforce</p></li>
<li><p>Holidays</p></li>
<li><p>Department manager has a backlog of work</p></li>
</ul></td>
</tr>
</tbody>
</table>



> [!TIP]
> <P>There is only one type for all reason codes for personnel actions. Be sure to enter all the reason codes that you want to offer for both position- and worker-related personnel actions. For more information about how to create reason codes, see <A href="https://technet.microsoft.com/library/aa590446(v=ax.60)">Human Resources reason codes (form)</A>.</P>



## 4\. Create a personnel action number sequence and associate it with personnel actions

Each time a user creates a personnel action, the action must be assigned a unique ID so that it can be easily identified. You can automate this process by creating a number sequence and assigning it to personnel actions.


> [!WARNING]
> <P>If you don’t complete this step, users will still be able to perform the action, but they will have to enter the ID manually. This can become difficult over time because each ID must be unique.</P>



To set up a number sequence and associate it with personnel actions, follow these steps:

1.  Create a number sequence for personnel actions. If you’re not familiar with how to set up a new number sequence, see [Number sequence overview](number-sequence-overview.md).

2.  In the **Human resources shared parameters** form, assign the number sequence that you created to the **Personnel action** reference.

3.  Close the form. When users create personnel actions, the next available number in the number sequence is assigned to the action.

## Next step

After you have set up and tested the items described in this topic, users can enter personnel action types and submit their requests to workflow, if it is required. For more information, see [Assign personnel actions to workers](https://technet.microsoft.com/library/dn479033\(v=ax.60\)).

## Related tasks

[Assign personnel actions to workers](https://technet.microsoft.com/library/dn479033\(v=ax.60\))

[Personnel actions](personnel-actions.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><a href="personnel-actions-configuration-key-hcmpersonnelactions.md">Personnel actions configuration key (HcmPersonnelActions)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Human resource assistant (HcmHumanResourceAssistant) can create personnel action types, configure personnel action workflows, and create personnel actions.</p></td>
</tr>
</tbody>
</table>


## See also

Set up Human resources workflows

  


