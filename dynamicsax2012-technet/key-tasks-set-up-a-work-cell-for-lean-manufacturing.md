---
title: 'Key tasks: Set up a work cell for lean manufacturing'
TOCTitle: 'Key tasks: Set up a work cell for lean manufacturing'
ms:assetid: 2af1e8c0-d77b-418f-8f7f-0c84a93a7a1d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208503(v=AX.60)
ms:contentKeyID: 36056241
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- assign work cell
- configure a work cell
- configure work cell capacity
- create a production flow model
- lean manufacturing capacity
- lean manufacturing work cell
- process activity
- set up work cell
- work cell capacity
- process kanban job
- work cell
- resource group capacity
---

# Key tasks: Set up a work cell for lean manufacturing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure resource groups to function as work cells where process kanban jobs for lean manufacturing are performed. Kanban jobs are then assigned to the work cell that is defined on the referenced process activity.

The procedure for setting up a work cell includes the following tasks:

## What do you want to do?

Create a production flow model

Configure a work cell

Configure the capacity settings for the work cell

Find form help

## Create a production flow model

When you set up a work cell for lean manufacturing, you must assign a production flow model. The production flow model defines the capacity settings that are used to schedule kanban jobs. The production flow model also defines how the schedule for the work cell is structured and displayed in the **Kanban schedule board**.

1.  Click **Production control** \> **Setup** \> **Lean manufacturing** \> **Production flow models**.

2.  Click **New** to create a model.

3.  In the **Model type** field, select the method that is used to measure capacity for the work cell.

4.  Define the every product every (EPE) cycle. This is used to calculate the period when a kanban job is scheduled.

5.  In the **Kanban schedule** tab, define the following settings:
    
      - In the **Capacity shortage reaction** field, select the method of scheduling to use when no capacity is available during the required period.
    
      - The parameters that define the structure of the kanban schedule for a work cell.

6.  Save the model.

Back to top

## Configure a work cell


> [!TIP]
> <P>Before you can configure a work cell, the following preconditions must be met:</P>
> <UL>
> <LI>
> <P>The warehouses and locations that are referenced by the resource group are created. See <A href="create-warehouses.md">Create warehouses</A> and <A href="create-locations.md">Create locations</A> for more information.</P>
> <LI>
> <P>A working time calendar is created, and the calendar has a standard work day defined. See <A href="create-working-time-calendars.md">Create working time calendars</A> for more information.</P></LI></UL>



1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Create a resource group. See [Set up and define resource groups for operations resources](set-up-and-define-resource-groups-for-operations-resources.md) for more information.

3.  On the **General** FastTab, select the **Work cell** check box to define the resource group as a work cell.

4.  In the **Locations** field group, select the default warehouses and locations that you want to use. The **Input warehouse**, **Input location**, **Output warehouse**, and **Output location** fields are mandatory.

5.  If you want to track direct labor costs, you must define a run time cost category. On the **Operation** FastTab, select a category in the **Run time category** field.

6.  On the **Calendars** FastTab, assign a working time calendar and expiration date.
    

    > [!TIP]
    > <P>You must complete this step before you can create a version of a production flow. If you do not assign a calendar, you cannot activate the version and an error message is displayed.</P>



7.  If the work cell is managed by a subcontractor, you must assign a vendor resource to the work cell. On the **Resources** FastTab, in the **Resource** field, select a resource that has the type, Vendor.

8.  Save the work cell.

Back to top

## Configure the capacity settings for the work cell

1.  On the **Resource groups** form, on the **Work cell capacity** FastTab, click **Add** to define a period during which the capacity of the resource group can be used for lean manufacturing.
    
    Outside of these periods, the capacity of the resource group can be used for non-lean manufacturing.

2.  Select the production flow model to use for the work cell. The model defines how the capacity of the work cell is measured. This field is mandatory.
    
    If you want to measure the throughput of the work cell, you must also define the **Capacity period**, **Average throughput quantity**, and **Unit** fields.

3.  Enter the dates to define the period when the capacity of the work cell is in effect.

4.  Save the settings.

Back to top

## Find form help

[Production flow model (form)](https://technet.microsoft.com/en-us/library/hh209069\(v=ax.60\))

[Resource groups (form)](https://technet.microsoft.com/en-us/library/hh227450\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

