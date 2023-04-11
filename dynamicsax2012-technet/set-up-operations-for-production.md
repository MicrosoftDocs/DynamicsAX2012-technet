---
title: Set up operations for production
TOCTitle: Set up operations for production
ms:assetid: cca9d996-f6b0-443b-8d1a-def42ef66723
ms:mtpsurl: https://technet.microsoft.com/library/Aa572676(v=AX.60)
ms:contentKeyID: 37832534
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- operation
- production
audience: Application User
ms.search.region: Global
---

# Set up operations for production 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Operations represent the tasks that are required to produce items in your production. To set up operations, you must know what task or activity is being completed, the order of the process and operation priorities, and which and how many resources perform the operation.

## Creating routes

You can set up operations to form different kinds of routes, depending on your production processes. A route is a series of operations linked in sequence, and describes the route the item must take through the manufacturing process to emerge as a finished product. You can work with two kinds of routes. The routes are controlled by the **Route network** check box in the **Production control parameters** form:

  - Simple sequence – Unless specified, each operation in the route is completed before the next operation is begun. This option is used if the **Route network** check box is not selected.

  - Complex route where parallel operations are allowed – When it is necessary, operations in the route can be set up in parallel. This option is used if the **Route network** check box is selected.

## Set up an operation

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**.

2.  Click **New** on the toolbar to create a new line.

3.  In the **Operation** field, enter an alphanumeric identifier for the operation that you want to create.

4.  In the **Name** field, enter the name of the operation.

## Define an overview of operation relations

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**. Click **Relations**.

2.  On the **Overview** tab, in the **Item code** field, select the item code:
    
      - **Table** – The operation refers to a single item with a specific item number.
    
      - **Group** – The operation refers to a group of items within a given Item - Customer group.
    
      - **All** – The operation can be used on all items.

3.  If you selected **Table** or **Group** in step 2, in the **Item relation** field, select the item number or item group that you want to use for the operation. Otherwise, leave the field blank.

4.  If you selected **Table** in step 2, in the **Configuration** field, enter the configuration, or the item's dimension, to use for the operation. Otherwise, leave the field blank.

5.  In the **Route code** field, select the kind of association the operation has with the route:
    
      - **Route** – Associate the operation with a single route.
    
      - **All** – Associate the operation with all routes.

6.  If you selected **Route** in step 5, in the **Route relation** field, enter the number to use for the operation. Otherwise, leave the field blank.

7.  In the **Route group** field, select the routing group to use for the operation. Routing groups control how the operation is calculated, how the feedback is provided on the operation, and how the operation is scheduled and job-managed.

## Define general operation relations

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**. Click **Relations**.

2.  Click the **General** tab. In the **Item code** field, you can view the item code that you selected for the operation. This field is automatically completed with information from the **Overview** tab.
    
      - **Table** – The operation refers to a single item with a specific item number.
    
      - **Group** – The operation refers to a group of items within a given Item - Customer group.
    
      - **All** – The operation can be used on all items.

3.  In the **Item relation** field, you can view the item number or item group that you selected for the operation. This field is automatically completed with information from the **Overview** tab, but you can change it here if you want to.

4.  If **Table** is selected in the **Item code** field, in the **Configuration** field, enter the configuration to use for the operation. Otherwise, leave the field blank.

5.  In the **Route code** field, view the association that the operation has with the route. This field is automatically completed with information from the **Overview** tab, but you can change it here if you want to.
    
      - **Route** – Associate the operation with a single route.
    
      - **All** – Associate the operation with all routes.

6.  If you selected **Route** in step 5, in the **Route relation** field, view the number that the operation has. This field is automatically completed with information from the **Overview** tab, but you can change it here if necessary.

7.  In the **Operation** field, view the operation that you are setting up. This field is automatically completed with information from the **Overview** tab, but you can change it here if you want to.

8.  In the **Site** field, select the site on which you are setting up operations information. You can create an operation relation that is valid for all sites by leaving the **Site** field empty, or you can create an operation relation that is specific to one site only by selecting a site in the field. Route versions must be site-specific.

9.  In the **Property** field, if applicable, select the operation characteristics to use when the operation is being planned.
    
    Operation properties are values from the properties table specified in the calendar. When you schedule a production order, the operation with the defined property can be scheduled only during time intervals where the same property value is specified in the calendar. You can use this to control how operations are sequenced.
    

    > [!NOTE]
    > <P>To schedule by using properties, you must select the <STRONG>Finite property</STRONG> check box on the resource and in the settings for production scheduling.</P>



10. In the **Route group** field, select the routing group to use for the operation.

11. In the **Route type** field, select one of the following:
    
      - If the operation engages a vendor, select **Vendor**.
    
      - If the operation is internal, select **Standard**.

## Define the operation relation setup

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**. Click **Relations**.

2.  Click the **Setup** tab, and in the **Formula** field, select the method that is used to calculate the run time for the operation:
    
      - **Standard** – Use manually entered values for the run time.
    
      - **Capacity** – Calculate the run time based on the capacity specified on the resource, and the **Run time** and **Factor** fields for the operation.
    
      - **Batch** – Calculate the run time based on the values in the **Run time**, **Process qty.**, and **Factor** fields, together with the order quantity.
    
      - **Resource batch** – Calculate the run time based on the **Batch capacity** and **Capacity** values from the resource, and the **Run time** and **Factor** fields from the operation.

3.  In the **Factor** field, enter the formula factor to use for the operation.
    
    The formula factor is used when **Capacity** is selected in the **Formula** field. The capacity value from the resource is then divided by the factor value to calculate the process quantity. A value of 0 is disregarded.

4.  In the **Costing resource** field, select the resource that you want to base estimation and BOM calculation on. When the operation is scheduled, estimation and BOM calculation use the resource that is actually scheduled. Default values from the selected resource are transferred to the form, but you can change these default values if necessary.

5.  In the **Setup** field, select the cost category to use for the setup costs of the operation.

6.  In the **Run** field, select the cost category to use as an estimate of the cost of run time associated with the operation.

7.  In the **Quantity** field, select the quantity category to use when the operation is conducted. The quantity category designates the cost price for each unit of finished item that was used in the estimate of the production order associated with the operation.

## Define operation relation times

If you selected a costing resource in the **Costing resource** field on the **Setup** tab, and you inserted default values, all fields on the **Times** tab display the values specified for the selected costing resource. You can change the value in any field if you want to.

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**. Click **Relations**.

2.  Click the **Times** tab, and in the **Queue time before** field, enter the time that the operation must wait before it can start.

3.  In the **Setup time** field, enter the time that is required to set up the resource before the operation starts.

4.  In the **Run time** field, enter the time that is required to produce the process quantity on the resource.

5.  In the **Process qty.** field, enter the quantity that can be produced during the time specified in the **Run time** field.
    

    > [!NOTE]
    > <P><STRONG>Run time</STRONG> and <STRONG>Process qty.</STRONG> are interdependent fields. One value cannot exist without the other.</P>



6.  In the **Transit time** field, enter the transportation time that is used to move the item from one operation to another, or from one resource to another.

7.  In the **Queue time after** field, enter the time that the item waits at the resource after the operation is completed.

8.  In the **Hours/time** field, enter the time to use for the operation. This time is presented in hours with four decimals.

9.  In the **Transfer batch** field, enter the quantity of finished items that can be moved between operations. This quantity is also used to calculate the overlap quantity during estimation of production orders.

## Add resource requirements to operation relations

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**. Click **Relations**.

2.  Click the **Resource requirements** tab, and then click **New**.

3.  In the **Quantity** field, enter the number of resources that are required to perform the operation.

4.  In the **Load** field, enter the percentage of the maximum capacity load that must be reserved for the operation.

5.  In the **Requirement type** field, select a requirement type. The requirement type you select affects the options that you have in the remaining fields.

6.  In the **Requirement** field, select the requirement for the operation. Depending on the selection in the **Requirement type** field, this can be one of the following: a resource type, resource, resource group, capability, skill, course, certificate, or title.

7.  Select the **Operation scheduling** check box if you want to use this requirement for operations scheduling.
    

    > [!NOTE]
    > <P>You can only use resource, resource group, resource type, and capability requirements for operations scheduling.</P>



8.  Select the **Job scheduling** check box if you want to use this requirement for job scheduling. You can use all resource requirements for job scheduling. By default, the **Operation scheduling** and **Job scheduling** check boxes are selected. You can clear them if you want to.

## Add descriptive information to operation relations

1.  Click **Production control** \> **Setup** \> **Routes** \> **Operations**. Click **Relations**.

2.  Click the **Description** tab, and enter a detailed description of the operation in the available field.

## See also

[Operation relation (form)](https://technet.microsoft.com/library/aa584158\(v=ax.60\))

  


