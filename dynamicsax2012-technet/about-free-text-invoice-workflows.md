---
title: About free text invoice workflows
TOCTitle: About free text invoice workflows
ms:assetid: 4580dc61-a128-425f-9c1e-b863aa1c1383
ms:mtpsurl: https://technet.microsoft.com/library/Hh242381(v=AX.60)
ms:contentKeyID: 36056894
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- overview of free text invoice workflow
- workflow type
- workflow, free text invoice overview
audience: Application User
ms.search.region: Global
---

# About free text invoice workflows 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up a workflow for free text invoices to require that free text invoices be submitted for approval. You can require that all free text invoices be submitted, or only those that meet specified conditions.


> [!NOTE]
> <P>If you do not want any free text invoices to be submitted for review, do not set up a workflow for free text invoices.</P>



Even if your organization submits free text invoices for review, you can create conditional statements in the workflow so that some invoices are automatically approved in certain situations. For example, you might specify a condition where, if the invoice total is less than 500.00, the invoice can be approved without user intervention. Also, the workflow that you set up determines which users, if any, must approve the invoice, and when to route the invoice through the workflow process.


> [!NOTE]
> <P>Before you complete the procedures in this topic, you should be familiar with the general workflow functionality. For more information, see <A href="workflow-for-microsoft-dynamics-ax.md">Workflow for Microsoft Dynamics AX</A>.</P>



The configuration of the workflow varies from organization to organization, as do business processes. Therefore, you must configure the workflows to match the business processes for free text invoices in your organization.

The following examples illustrate workflows that are frequently used by organizations for free text invoice approvals.

## Example: Configure a workflow where free text invoices must be approved by a user

This example explains how to create a workflow in which a user must approve all free text invoices, regardless of the invoice amount.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable workflows**.

2.  On the Action Pane, click **New**.

3.  Select **Customer free text invoice workflow** and then click **Create workflow**.

4.  In the workflow editor, click **Properties** on the Action Pane.

5.  Enter the following flowchart properties in the **Properties** form:
    
      - **Name** – Enter Free text invoice approval regardless of amount.
    
      - **Submission instructions** – Enter Click Submit to submit the invoice for approval.

6.  Click **Close**.

7.  In the **Workflow elements**, drag the **Approve free text invoice** element to the **Start** and **End** elements.
    

    > [!NOTE]
    > <P>If you do not drag the <STRONG>Approve free text invoice</STRONG> element directly to the <STRONG>Start</STRONG> and <STRONG>End</STRONG> elements, you will have to manually connect the flowchart lines to make sure that the process is completed.</P>



8.  Right-click the **Approve free text invoice** element in the flowchart and then click **Properties**.

9.  Change the name to All free text invoices require approval.

10. Click **Close**.

11. Double-click the **All free text invoices require approval** element to expand it. Right-click the Step 1 element and then click **Properties**. Enter the following properties:
    
      - **Name** – Enter Approve or reject the invoice.
    
      - **Work item subject** – Enter This invoice requires your approval.
    
      - **Work item instructions** – Enter Click the Approve, Reject, or History menu item.

12. Click **Assignment** and select **User** from the **Assign users to this workflow element** list.

13. Click the **User** tab and assign the workflow element to yourself. Select your user ID in the **Available users:** list and then click the **\>** button to move your ID to the **Selected users:** list.

14. Click the **Time limit** tab and enter the following field information:
    
      - **Calendar name** – Select **Work calendar due dates**.
    
      - **Calendar** – Select any available calendar from the list.

15. Click **Close**.

16. Close the workflow editor.

17. When prompted, enter any version notes and then click **OK**.

18. Click **Activate the new version** and then click **OK**. From this point on, all free text invoices must be submitted for approval.

## Example: Configure a workflow for free text invoices where user approval is required only for high invoice amounts

This example explains how to create a workflow in which a user must approve a free text invoice if the invoice total is more than 1,000.00. Invoices that have a total amount of 1,000.00 or lower will automatically have an **Approved** status after they are submitted to workflow.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable workflows**.

2.  On the Action Pane, click **New**.

3.  Select **Customer free text invoice workflow** and then click **Create workflow**.

4.  In the workflow editor, click **Properties** on the Action Pane.

5.  Enter the following flowchart properties in the **Properties** form:
    
      - **Name** – Enter The invoice total exceeds 1,000 and requires approval.
    
      - **Submission instructions** – Enter Click Submit to submit the invoice for approval.

6.  Click **Close**.

7.  In the **Workflow elements**, drag the **Approve free text invoice** element to the **Start** and **End** elements.
    

    > [!NOTE]
    > <P>If you do not drag the <STRONG>Approve free text invoice</STRONG> element to the <STRONG>Start</STRONG> and <STRONG>End</STRONG> elements, you will have to manually connect the flowchart lines to make sure that the process is completed.</P>



8.  Right-click the **Approve free text invoice** element in the flowchart and then click **Properties**.

9.  Change the name to Free text invoices \> 1,000.

10. Click **Close**.

11. Double-click the **Free text invoices \> 1,000** element to expand it. Right-click the Step 1 element and then click **Properties**. Enter the following properties:
    
      - **Name** – Enter Approve or reject the invoice.
    
      - **Work item subject** – Enter This invoice requires your approval.
    
      - **Work item instructions** – Enter Click the Approve, Reject, or History menu item.

12. Click **Assignment** and select **User** from the **Assign users to this workflow element** list.

13. Click the **User** tab and assign the workflow element to yourself. Select your user ID in the **Available users:** list and then click the **\>** button to move your ID to the **Selected users:** list.

14. Click the **Time limit** tab and enter the following field information:
    
      - **Calendar name** – Select **Work calendar due dates**.
    
      - **Calendar** – Select any available calendar from the list.

15. Click **Condition** and enter the following field information:
    
      - Select **Run this step only when the following condition is met**.
    
    <!-- end list -->
    
      - Add a condition where **Customer free text invoice**.**Invoice total** \> 1000.

16. Click **Close**.

17. Close the workflow editor.

18. When prompted, enter any version notes and then click **OK**.

19. Click **Activate the new version** and then click **OK**. From this point on, all free text invoices must be submitted for approval. Those with invoice amounts that exceed 1,000 will require approval, and those with invoice amounts of 1,000 or less will automatically be approved.


> [!NOTE]
> <P>The user will have to wait for a short time for the automatic approval process to be completed before they can post the invoices.</P>



## See also

[Workflow for Microsoft Dynamics AX](workflow-for-microsoft-dynamics-ax.md)

[Set up Accounts receivable workflows](set-up-accounts-receivable-workflows.md)

  


