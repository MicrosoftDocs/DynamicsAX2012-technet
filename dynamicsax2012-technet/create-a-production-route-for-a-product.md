---
title: Create a production route for a product
TOCTitle: Create a production route for a product
ms:assetid: 2318142f-a1a6-451b-99bd-524a228a5a5d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ838726(v=AX.60)
ms:contentKeyID: 50120609
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create a production route for a product [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create a production route for a released product. You can define one or more operations for the route. You can then assign a resource or resource group to the operation for the route.


> [!NOTE]
> <P>If you assign a resource to an operation for the route, the resource must be available in a resource group in order to reference a working time calendar.</P>



You can assign a sequence group to a resource or resource group. For more information, see [Assign a sequence group to an operation resource or resource group](assign-a-sequence-group-to-an-operation-resource-or-resource-group.md). You can assign a sequence group to a resource group, and then assign another sequence group to a resource within that resource group. When you assign the resource group as the requirement type for an operation in the route, the sequencing of operations is performed based on the sequence group assigned to the resource group.


> [!NOTE]
> <P>When you assign multiple resources and resource groups to an operation, only the first operation that has a primary resource or resource group is sequenced; all other operations with or without resources or resource groups that have sequence groups are ignored.</P>



1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select or create a released product. For more information, see [Key tasks: Define products](key-tasks-define-products.md).

3.  On the **Action Pane**, click the **Engineer** tab, and then click **Route** to open the **Route** form.

4.  In the **Route number** field, select the route to assign to the released product.

5.  In the **Name** field, enter the name of the route.

6.  In the **Site** field, select a site for the route.

7.  In the lower pane, click **New** to create an operation for the route, and then update information in the following fields:
    
    1.  In the **Oper. No** field, enter the operation number. The operation number is an alphanumeric string of up to 10 characters. The operation number defines the order that the production follows. When you create a new production route, 10 is updated as the first operation number. The numbers for successive operations are updated in increments of 10. You can change the operation numbers manually. To create simultaneous operations, you must use the same operation number for all the operations. You create simultaneous operations for situations in which multiple resources, such as a machine and a tool, are used at the same time.
    
    2.  In the **Priority** field, select the priority of the operation. The priority defines the order in which operations are performed when two or more operations require the same resources at the same time.
    
    3.  In the **Operation** filed, select the identification code of the operation that is assigned to the route.
    
    4.  In the **Process qty.** field, enter the quantity of items that are produced during the defined process time.
    
    5.  In the **Next** field, enter next operation number in the route network. This field indicates the operation that follows the selected operation. The last operation in the route is defined as 0 (zero).
    
    6.  In the **Route group** field, select the identification code of the route group that controls the operation. Route groups control calculation, scheduling, job management, and reporting for operations.
    
    7.  Click the **Resource requirement** tab, and then in the **Quantity** field, enter the number of resources that are required for the route.
    
    8.  In the **Load** field, enter a percentage as the maximum capacity that is assigned to the resource for the operation.
    
    9.  Click **New** to assign a resource or resource group to the operation.
    
    10. In the **Requirement type** field, select the requirement type. The following options are available:
        
          - **Resource type**
        
          - **Resource**
        
          - **Resource group**
        
          - **Capability**
        
        If you are using the Human resources module, the following additional options are available:
        
          - **Skill**
        
          - **Course**
        
          - **Certificate**
        
          - **Title**
    
    11. In the **Requirement** field, select the requirement for the resource.
    
    12. Select the **Operations scheduling** check box to use the requirement for operation scheduling.
    
    13. Select the **Job scheduling** check box to use the requirement for job scheduling.
    
    14. Repeat steps i through m to assign additional resources or resource groups.

8.  Repeat step 7 to assign additional operations to the route.

## See also

[(PM) Released product details (form)](https://technet.microsoft.com/en-us/library/hh352306\(v=ax.60\))

[Route groups (form)](https://technet.microsoft.com/en-us/library/aa596433\(v=ax.60\))

[Route (form)](https://technet.microsoft.com/en-us/library/aa550121\(v=ax.60\))

[Operations (form)](https://technet.microsoft.com/en-us/library/aa548958\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

