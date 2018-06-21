---
title: Create and maintain operations resources
TOCTitle: Create and maintain operations resources
ms:assetid: fbe81833-27f0-4163-9ae2-278005a8a01d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa499880(v=AX.60)
ms:contentKeyID: 36060086
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- resource
- resources
- operation
- production
- operations
---

# Create and maintain operations resources [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Operations resources are resources used to complete the production process. Create operations resources after you create the operations resource groups and before you begin production.


> [!NOTE]
> <P>For complete information about the buttons on this form, see <A href="https://technet.microsoft.com/en-us/library/aa557962(v=ax.60)">Resources (form)</A>.</P>



## Create an operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Click **Resource** on the **Resource** tab on the Action Pane to create a line.

3.  In the **Resource** field, type an alphanumeric identifier for the operations resource you want to create.

4.  In the **Description** field, enter a description of the operations resource.

5.  In the **Name** field, select the operations resource type from the drop-down list.

6.  If you select the resource type **Vendor**, in the **Vendor** field on the **General** tab, select the vendor this resource represents. If not, leave this field blank.

7.  If you are using the Human Resources module, and you want to select the resource type **Human resources**, you can then select the worker that this resource represents in the **Send list of products** field on the **General** tab.

## Set up general information for an existing operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the **Resource** you want to set up general information for and then click the **General** tab.

3.  Under **Resource**:
    
    1.  If you select the resource type **Vendor**, in the **Vendor** field, select a vendor from the list.
        
        If you selected some other resource type, leave this field blank.
    
    2.  If you select the resource type **Human resources**, in the **Send list of products** field, select a worker from the list.
        
        If you selected some other resource type, leave this field blank.

4.  Under **Scheduling**:
    
    1.  In the **Efficiency percentage** field, enter a percentage that represents how well you expect the resource to produce the planned amount. Efficiency is used to adjust run time during planning.
    
    2.  In the **Operations scheduling percentage** field, type the percent of the capacity of the resource you want to use in operations scheduling.
        
        This should be less than 100 percent to allow for flexibility in capacity when job scheduling.
    
    3.  Select the **Finite capacity** field, if you want the resource to be scheduled based on the capacity actually available.
        

        > [!WARNING]
        > <P>If you leave this field blank, the system assumes that all capacity needed for this resource is available during scheduling. This can result in over booking the resource.</P>

        
        When you select this field you tell the system to use finite capacity scheduling for this resource.
    
    4.  Select the **Finite property** field if you want the system to take the properties on this resource into consideration when scheduling.
    
    5.  Select the **Exclusive** field if you do not want the resource to be available for another job or operation until the current production is completed. This means that the resource cannot be used even if there are gaps in the resource's run time.

5.  Under **Capacity**:
    
    1.  Enter a number in the **Capacity** field if you want to measure capacity for the resource, according to the capacity unit selected in the next field.
        
        If you do not enter a number here, capacity is measured in hours according to the calendar.
    
    2.  Select a unit in the **Capacity unit** field, if applicable.
        
        This is the unit of measure used by the system to calculate the rate at which the resource can produce an item.

## Set up ledger information for an existing operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the resource you want to set up ledger information for and then click the **Ledger** tab.

3.  Under **Accounts - WIP**:
    
    1.  In the **WIP issue** field, select the account to use for the work-in-process (WIP) issue from the list.
    
    2.  In the **WIP account** field, select the WIP account you want to use for the resource from the list.

4.  Under **Accounts - costing**:
    
    1.  In the **Issue** field, select the account you want to use for resource issues from the list.
    
    2.  In the **Offset account** field, select the offset account you want to use for resource issues from the list.

## Set up operation information for an existing operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the resource you want to set up operation information for and then click the **Operation** tab.

3.  Under **Route**:
    
    1.  In the **Route group** field, select the routing group you want to associate with the resource.
        
        If routing groups have not been created yet, this step can be done later.
    
    2.  In the **Scrap percentage** field, enter a percent that represents the amount of scrap material left over when the resource has finished an operation.
        
        For example, if shirts are cut from fabric and the pieces that are used amount to eight tenths of the fabric (0.80), the scrap percent is 0.20 or 20%.

4.  Under **Cost categories**:
    
    1.  In the **Setup category** field, from the list, select the cost group for the setup costs associated with this resource.
        
        Use this and the next two fields to manage and identify the costs used in production.
    
    2.  In the **Run time category** field, from the list, select the cost group for the run time costs associated with this resource.
    
    3.  In the **Quantity category** field, from the list, select the cost group for the costs associated with the quantities produced by this resource.

## Set up times information for an existing operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the resource you want to set up times information for and then click the **Operation** tab.

3.  Under **Times**:
    
    1.  In the **Queue time before** field, type the time that is required for the job to wait at the resource before setup or work is performed.
    
    2.  In the **Setup time** field, type the time that is required to refit the equipment or prepare the resource for the production of the next scheduled item.
    
    3.  In the **Run time** field, type the time that is required to process a piece or lots of a specific operation on this resource.
    
    4.  In the **Process qty.** field, type the process quantity. This is the quantity that can be produced in the times listed in the **Setup time** and **Run time** times fields.

4.  Under **Overlap**:
    
    In the **Transfer batch** field, type the overlap quantity. This is the quantity to be produced before the next operation in the production route can begin.

## Set up Financial dimensions for an existing operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the resource you want to set up financial dimensions for and then click the **Financial dimensions** tab.

3.  Under **Default financial dimensions**, select the dimensions that you want to use as default for the item in the resource.

## Assign capabilities to an existing operations resource

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the resource you want to assign capabilities to and then click the **Capabilities** tab.

3.  On the **Capabilities** tab, click the **Add** button to assign a new capability to the selected resource.

4.  In the **Reference** field, select the capability you want to assign.

5.  Edit capability values: You can change the values for the selected resource if you want to.

6.  In the **Effective** field, set the start date the resource can be scheduled for production based on the assigned capability. Once this date has been passed, you cannot change the other field values of the capability.

7.  In the **Expiration:** field, set the last date the resource can be scheduled for production based on the assigned capability.

8.  In the **Grade** field, set the level of the capability for the selected resource.

9.  In the **Priority** field, define the priority of the selected resource with respect to the capability.


> [!NOTE]
> <P>If <STRONG>Priority</STRONG> is selected in the <STRONG>Primary resource selection</STRONG> field on the <STRONG>Scheduling parameters</STRONG> form, the engine will select the resource with the lowest numeric value (highest priority) first during scheduling.</P>



## Assign an operations resource to a resource group

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resources**.

2.  Select the resource you want to add to a resource group, and then click the **Add to resource group** button on the Action Pane.

3.  In the **Group** field, select the resource group you want to assign the resource to.

4.  Edit default group values: Default values for the resource group are transferred automatically but you can override the default values for the selected resource if you want to.

5.  In the **Effective** field, define the start date when the resource is considered to be part of the resource group.

6.  In the **Expiration:** field, set the last date when the resource is no longer a assigned to the resource group.

7.  In the **Calendar** field, select the calendar that you want to use for the resource.

## See also

[Set up and define resource groups for operations resources](set-up-and-define-resource-groups-for-operations-resources.md)

[Copy an existing operations resource](copy-an-existing-operations-resource.md)

[Bulk edit resources](bulk-edit-operations-resources.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

