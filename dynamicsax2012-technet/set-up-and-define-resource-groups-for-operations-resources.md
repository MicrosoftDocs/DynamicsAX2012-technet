---
title: Set up and define resource groups for operations resources
TOCTitle: Set up and define resource groups for operations resources
ms:assetid: 7bf9e8b9-66fe-4b4b-9754-ff57ebcec48d
ms:mtpsurl: https://technet.microsoft.com/library/Aa571511(v=AX.60)
ms:contentKeyID: 36058261
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up and define resource groups for operations resources 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You should create resource groups before you create the operations resources that you will use in your production. These groups should be organized according to the logic and complexity of your manufacturing environment. The operations resources in a group should perform similar functions and share similar attributes so that they can be used interchangeably during scheduling.

For example, you can group machines and machine operators that do the same type of work at the same capacity in one group and machines and machine operators that have other skills and capacities in another group. When you schedule production, you can select any machine or operator in the group to perform the operation.

You can also use resource groups to manage system information. For example, if you post a particular resource group to the ledger, you do not have to post financial data for each of the operations resources individually.

## Create a resource group

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Press CTRL+N to create a new line in the **Resource group** table.

3.  In the **Resource group** field, enter a unique alphanumeric identifier for the new resource group.

4.  In the **Description** field, enter a description for the resource group.

5.  In the **Site** field, select the site where the resource group is located.

## Set up general information for a resource group

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select the resource group that you want to set up general information for.

3.  Click the **General** FastTab.

4.  In the **Production unit** field, select the production unit that the resource group is a member of. You can select only production units that are defined for the same site as the resource group is.

5.  In the **Locations** field group, provide the following information:
    
      - In the **Input warehouse** field, select the input warehouse. You can select only warehouses that are on the same site as the resource group.
    
      - In the **Input location** field, select the input location in the input warehouse.
    
      - In the **Output warehouse** field, select the output warehouse. You can select only warehouses that are on the same site as the resource group.
    
      - In the **Output location** field, select the output location in the output warehouse

6.  In the **Scheduling** field group, provide the following information:
    
      - In the **Efficiency percentage** field, enter a percent that represents the resource group's efficiency. This information is used for planning in the calendar.
    
      - In the **Operations scheduling percentage** field, enter a percent that represents the maximum capacity of the resource group that you want to use in operation scheduling.
        
        This value should be less than 100 percent in order to allow for flexibility in capacity when job scheduling, which is performed closer to the actual time of the scheduled production. A value of around 50 percent is generally used.
    
      - Select the **Finite capacity** check box if you want this resource group to be used with limited capacity. If this check box is cleared, the system does not consider the capacity of this resource group during scheduling.
    
      - Select the **Bottleneck resource** check box if you want this resource group to be considered a bottleneck resource.

7.  In the **Capacity** field group, provide the following information:
    
      - In the **Capacity unit** field, select the unit that the capacity is to be measured in.
    
      - In the **Capacity** field, enter the capacity per hour in capacity units.
    
      - In the **Batch capacity** field, enter the batch capacity of the resource.

## Set up operation information for a resource group

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select the resource group that you want to set up operation information for.

3.  Click the **Operation** FastTab.

4.  In the **Scrap percentage** field, enter a percent that represents the amount of scrap material left over by the operations resource.
    
    For example, if eight-tenths (0.80) of a bolt of fabric is used for shirts, the scrap percent is 0.20 or 20 percent.

5.  In the **Setup category** list, select the cost group for the setup costs that is associated with this resource.
    

    > [!NOTE]
    > <P>This field and the next two fields must be completed if you want to manage and identify the costs used in production.</P>



6.  In the **Run time category** list, select the cost group for the run time costs that are associated with this operations resource.

7.  In the **Quantity category** list, select the cost group for the costs that are associated with the quantities produced by this operations resource.

## Set up ledger information for a resource group

The information on the **Ledger** FastTab depends on the accounting method that was used. These fields are required if the method is **Item and resource**. These fields are not required if the method is **Item and category** or if production groups are used.

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select the resource group that you want to up ledger information for.

3.  Click the **Ledger** FastTab.

4.  In the **WIP issue** list, select the account to use for the WIP (work-in-process) issue.

5.  In the **WIP account** list, select the work-in-process account to use for the resource group.

6.  In the **Issue** list, select the account to use for resource group issues.

7.  In the **Offset account** list, select the offset account to use for resource group issues.

## Set up financial dimension information for a resource group

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select the resource group that you want to define financial dimension information for.

3.  On the **Financial dimensions** FastTab, enter information about the cost center, department, and expense purpose that the resource group is associated with.

## Assign a calendar to a resource group

You must select the default work calendar for the resource group from the existing calendars. You can define when the calendar is to take effect for the resource group and when the calendar expires. You can assign more than one calendar to a resource group, but assigned calendars cannot overlap each other’s dates.

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select the resource group that you want to assign or re-assign a calendar to.

3.  Click the **Calendars** FastTab.

4.  In the **Calendar** field, select the calendar that you want to assign to the resource group.

5.  In the **Effective** field, define the first date on which the resource group will start to use the calendar.

6.  In the **Expiration** field, set the expiration date for the resource group. The resource group will not use the calendar after this date.
    

    > [!NOTE]
    > <P>If there are no effective working calendars for a resource group, for example if the last assigned calendar or the only assigned calendar has expired, you can no longer access the resources that are assigned to the resource group for production planning and operations scheduling.</P>



## Assign an operations resource to a resource group

You must assign at least one operations resource to a resource group. Resource groups are collections of resources that share common business needs. To schedule production on resources, a resource group must contain operations resources.

An operations resource can be assigned to a resource group for a limited time. An operations resource can also be assigned to multiple resource groups, but the start dates and end dates may not overlap. You cannot assign an operations resource to two different resource groups at the same time.

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**.

2.  Select the resource group that you want to assign or re-assign an operations resource to.

3.  Click the **Resources** FastTab, and then click **Add**.

4.  In the **Resource** field, select the operations resource that you want to assign to the resource group.

5.  In the **Expiration** field, select an expiration date for the operations resource.

6.  In the **Calendar** field, select a working calendar for the operations resource.

7.  In the **Input warehouse** field, select the location that is used for input for the operations resource.

8.  In the **Input location** field, select the location that is used for output from the operations resource.

## See also

[Resource groups (form)](https://technet.microsoft.com/library/hh227450\(v=ax.60\))

[Group calendar deviations (form)](https://technet.microsoft.com/library/aa558219\(v=ax.60\))

[Capacity reservations on resources or resource groups (form)](https://technet.microsoft.com/library/aa600753\(v=ax.60\))

  


