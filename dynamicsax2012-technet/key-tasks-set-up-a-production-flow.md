---
title: 'Key tasks: Set up a production flow'
TOCTitle: 'Key tasks: Set up a production flow'
ms:assetid: b2a13b52-ed32-42b9-b5ec-6c9ec57d3c71
ms:mtpsurl: https://technet.microsoft.com/library/Hh527161(v=AX.60)
ms:contentKeyID: 37823212
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- activate production flow version
- activity relations
- production flow activities
- deactivate production flow version
- validate production flow version
- production flow
- production flow version
- lean manufacturing
- configure production flow
- create production flow
- production flow activity
- relate activities
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up a production flow 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the tasks that you must complete to create and configure a production flow that can be used in lean manufacturing production or replenishment activities. The subtasks are listed in sequential order.

The Microsoft Dynamics AX lean manufacturing framework is based on production flows that describe production processes from the material stage through the finished product stage. A production flow consists of one or more activities that define the flow of material and products through a production or supply scenario. You can map business processes for products, product families, and services by modeling them as production flows. Before you can set up a production flow, the following master data must be configured in Microsoft Dynamics AX:

  - The inventory infrastructure must be configured for sites, warehouses, and locations.

  - Resource groups must be configured to function as work cells that run process activities for lean manufacturing. For more information, see [Key tasks: Set up a work cell for lean manufacturing](key-tasks-set-up-a-work-cell-for-lean-manufacturing.md).

## What do you want to do?

Learn more about...

Create a production flow

Create a production flow version

Create an activity for a production flow version

Relate the activities

Validate the production flow version

Activate the production flow version

Deactivate the production flow version

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About lean manufacturing](about-lean-manufacturing.md)

## Create a production flow

1.  Click **Production control** \> **Setup** \> **Lean manufacturing** \> **Production flows**.

2.  Click **New** to create a production flow.

3.  Define the parameters that identify and describe the production flow. These parameters include the legal entity, value stream, and production group that the production flow is assigned to.

4.  On the **Financial dimensions** FastTab, you can select the financial dimensions to assign to the production flow.

Back to top

## Create a production flow version

After you create a production flow, you can create multiple versions of the production flow. A version defines the following information:

  - The validity dates of the production flow

  - The takt and cycle parameters that are used to calculate the cycle times of the production flow

  - The activities that define the kanban jobs that must be performed for the production flow

  - The activity relations that define the sequence of activities in the production flow

<!-- end list -->

1.  In the **Production flows** form, select the production flow to create a version for.

2.  On the **Versions** FastTab, click **Add**.

3.  In the **Create new production flow version** dialog box, select the effective and expiration dates to apply to the version, and then click **OK**. The new version appears in the grid on the **Versions** FastTab.
    

    > [!TIP]
    > <P>You can also create a production flow version that copies an existing version and the activities that are configured for the version. In the <STRONG>Create new production flow version</STRONG> dialog box, the fields in the <STRONG>Copy from version</STRONG> field group are populated by default. Select the effective and expiration dates to apply to the new version, and then click <STRONG>OK</STRONG>.</P>



4.  On the **Versions** FastTab, click **Details**.

5.  In the **Production flow version details** form, define the cycle times and takt times to use for the version.

6.  Click **OK**.

Back to top

## Create an activity for a production flow version

A production flow consists of one or more activities. An activity defines the detailed requirements of a kanban job. An activity should accurately describe the actual production conditions and lead times.

1.  In the **Production flows** form, select the production flow to create an activity for.

2.  On the **Versions** FastTab, select a version, and then click **Activities**.

3.  In the **Production flow activities** form, click **New version activity**, and then select **Create new plan activity**.

4.  In the **Create new plan activity** wizard, on the **New activity** page, select the type of activity to create. A process activity describes a value-adding operation. A transfer activity describes the transfer of material or products to support process activities in a production flow. Some of the pages in the wizard vary, depending on whether you create a process activity or a transfer activity.

5.  If you create a transfer activity, complete the following pages in the wizard:
    
      - **Create transfer activity** – Define the parameters that are used to control inventory transactions for the activity.
    
      - **Assign transfer locations** – Define storage dimensions for the activity. You can also define settings for activities that are subcontracted.

6.  If you create a process activity, complete the following pages in the wizard:
    
      - **Create process activity** – Define the main parameters for the activity. These parameters include the work cells, vendor account information, and settings that are used to control inventory transactions for the activity.
    
      - **Assign picking activities** – Define the parameters that are used to register material consumption of the activity.

7.  For both transfer and process activities, complete the **Assign activity time** page to define activity time components for an activity. Activity times are used to determine the due dates of the corresponding kanban jobs that are generated, and the issue times for material in the picking list. Activity times can also be used to calculate service times for subcontracted activities.

8.  Click **Finish** to create the activity.

Back to top

## Relate the activities

If there are multiple activities in a production flow version, you must define the sequence of the activities by creating activity relations. An activity relation relates two activities by defining one activity as a predecessor activity, and the other activity as a successor activity. After you define an activity relation, you can configure a constraint that defines a period between the end of a predecessor activity and the start of a successor activity. The time constraint is used to calculate the scheduling of a kanban flow.


> [!NOTE]
> <P>If cumulative update 6 for Microsoft Dynamics AX 2012 R2 or later is installed, you can later modify the constraint value and the cycle time ratio for the production flow version. Changing the activity constraint time does not affect existing kanban jobs. The change is effective when new kanbans are created that have activity dependencies.</P>
> <P>If you change the constraints, you must recalculate the cycle times for the production flow version.</P>



1.  In the **Production flows** form, select the production flow to relate the activities for.

2.  On the **Versions** FastTab, select a version, and then click **Activities**. In the **Production flow activities** form, the existing activity relations are displayed.

3.  Select an activity, and then click the **Predecessors** or **Successors** FastTab.

4.  Click **Add predecessor** or **Add successor**. In the **Create activity relation** form, the **Predecessor** or **Successor** field group is enabled, depending on how you open the form. The selected activity is displayed.

5.  In the **Activity** field, select the activity to create a relation to, and then enter additional detailed information.

6.  Click **OK**.

Back to top

## Validate the production flow version

Validate a version of a production flow to perform the following tasks:

  - Ensure that the activities are configured correctly, and that the production flow version is ready to be activated.

  - Calculate the cycle times for all activities in the production flow.

You can perform this task manually. The task is also performed automatically when you activate a version of a production flow.

1.  In the **Production flows** form, select the production flow to validate.

2.  On the **Versions** FastTab, select the version to validate, and then click **Validate**.

3.  In the **Validate production flow** form, click **OK**.
    
    If the validation is successful, a message is displayed. If the validation fails, a message lists the reasons for the failure.

Back to top

## Activate the production flow version

When a version of a production flow is activated, it is ready to use in production or replenishment activities.

Only one version of a production flow can be active at a time. There can be multiple versions that are activated, but the validity dates cannot overlap.

1.  In the **Production flows** form, select the production flow to activate.

2.  On the **Versions** FastTab, select the version to activate. Click **Activation**, and then click **Activate**.

3.  In the **Activate production flow** form, click **OK**.
    
    If the activation is successful, the value in the **Plan status** field is **Active**. If the activation fails, a message lists the reasons for the failure.

Back to top

## Deactivate the production flow version

When a production flow version becomes obsolete, you can deactivate it if no active kanbans are outstanding.


> [!WARNING]
> <P>When you deactivate a version of a production flow, all active kanban rules that reference the version expire on the date and time of the deactivation.</P>



1.  In the **Production flows** form, select the production flow to deactivate.

2.  On the **Versions** FastTab, select the version to deactivate. Click **Activation**, and then click **Deactivate**.

3.  In the **Deactivate production flow** form, click **OK**.

If the deactivation fails, a message lists the active kanbans. If the deactivation is successful, the value in the **Plan status** field changes to **Draft**.

Back to top

## Find form help

[Sites (form)](https://technet.microsoft.com/library/hh242661\(v=ax.60\))

[Warehouses (form)](https://technet.microsoft.com/library/aa620570\(v=ax.60\))

[Inventory locations (form)](https://technet.microsoft.com/library/aa589646\(v=ax.60\))

[Resource groups (form)](https://technet.microsoft.com/library/hh227450\(v=ax.60\))

[Working times (form)](https://technet.microsoft.com/library/aa553844\(v=ax.60\))

[Production flow model (form)](https://technet.microsoft.com/library/hh209069\(v=ax.60\))

[Production flows (form)](https://technet.microsoft.com/library/hh208997\(v=ax.60\))

[Production flow version details (form)](https://technet.microsoft.com/library/hh209606\(v=ax.60\))

[Create new plan activity (form)](https://technet.microsoft.com/library/hh227522\(v=ax.60\))

[Production flow activities (form)](https://technet.microsoft.com/library/hh208824\(v=ax.60\))

[Create activity relation (form)](https://technet.microsoft.com/library/hh209655\(v=ax.60\))

[Validate production flow (class form)](https://technet.microsoft.com/library/hh209251\(v=ax.60\))

[Activate production flow (class form)](https://technet.microsoft.com/library/hh208818\(v=ax.60\))

[Deactivate production flow (class form)](https://technet.microsoft.com/library/hh227595\(v=ax.60\))

## Find related tasks

[Set up site and warehouse hierarchies](set-up-site-and-warehouse-hierarchies.md)

[Key tasks: Set up a work cell for lean manufacturing](key-tasks-set-up-a-work-cell-for-lean-manufacturing.md)

  


