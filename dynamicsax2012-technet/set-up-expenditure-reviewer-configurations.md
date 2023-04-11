---
title: Set up expenditure reviewer configurations
TOCTitle: Set up expenditure reviewer configurations
ms:assetid: 5976be66-ee71-48d9-a2eb-14c37d31cc9e
ms:mtpsurl: https://technet.microsoft.com/library/Hh208975(v=AX.60)
ms:contentKeyID: 36057348
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- configure reviewers
- expenditure reviewers
- purchase requisition expenditure reviewers
audience: Application User
ms.search.region: Global
---

# Set up expenditure reviewer configurations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up expenditure reviewer configurations to dynamically route expenditures for review based on the user who is assigned to a project role or a financial dimension where the expenditure is being charged. The workflow process uses the specified project role or financial dimension owner to determine whom to route the expenditure to.

You can define one or more expenditure reviewer configurations, and then select a configuration when you create a workflow. You can configure the expenditure reviewer values for every legal entity in your organization. After you define the expenditure reviewer configurations, you assign the configuration to your workflow task.


> [!NOTE]
> <P>You do not have to set up an expenditure reviewer configuration. You can assign a specific user or user group as reviewers when you define your workflow. However, if you have a complex organization, specifying expenditure reviewers can increase the efficiency of your approval process. It also eliminates the need to maintain your workflow reviewer assignments every time a reviewer changes job roles.</P>



## Set up expenditure reviewers

To set up expenditure reviewers follow the steps below:

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchase requisition expenditure reviewers**.

2.  In the **Purchase requisition expenditure reviewers** form, click **New**.

3.  Enter a name for the expenditure reviewer configuration and set the configuration values for each legal entity that is listed for your organization.

4.  Enter a name for the expenditure reviewer configuration and set the configuration values for each legal entity that is listed for your organization.

5.  When you create an expenditure reviewer configuration, you must enter values for each legal entity that is listed for your organization. If you do not enter values for a legal entity, and you add the expenditure reviewer configuration to your workflow setup, the workflow process will generate an error. The workflow process will be unable to determine which user to send the work item to.

6.  On the **Project distributions** FastTab, select the check box for the project role that will be responsible for reviewing purchase requisitions that are assigned to a project. You can select **Project manager**, **Project controller**, or **Project sales manager**. Expenditures will be routed to the user who is assigned to that role. You can also route the expenditure to the financial dimension owner by selecting the appropriate financial dimension check box.

7.  On the **Organization distributions** FastTab, select the check box for the financial dimensions that you want to use to route purchase requisitions that are not assigned to a project. Purchase requisitions will be routed to the user who owns the financial dimension.

## Assign expenditure reviewers to a workflow task

To assign expenditure reviewers to a workflow task follow the steps below:

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing workflows**.

2.  On the **Procurement and sourcing workflows** list page, double-click a workflow or create a new workflow.

3.  In the workflow editor, in the **Workflow** pane, select the task that you want to assign the expenditure reviewer configuration to, and then on the **Action Pane**, in the **Show** group, click **Properties**.

4.  In the left pane of the **Properties** form, click **Assignment**.

5.  On the **Assignment type** tab, select **Participant**.

6.  On the **Role based** tab, in the **Type of participant** field, select **Expenditure participants**. In the **Participant** field, select the expenditure reviewer configuration that you want to use for the workflow task.

For more information about how to configure workflow for expenditure review, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

## See also

[Expenditure reviewers - Purchase requisitions (form)](https://technet.microsoft.com/library/hh208667\(v=ax.60\))

  


