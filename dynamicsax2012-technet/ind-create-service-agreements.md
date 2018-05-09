---
title: (IND) Create service agreements
TOCTitle: (IND) Create service agreements
ms:assetid: 6b6c9caf-3c3c-4149-a693-d2f2a13dfd15
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677894(v=AX.60)
ms:contentKeyID: 49385857
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Create service agreements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a service agreement for a customer. The service agreement defines the resources for services and how those resources are invoiced to the customer. You can also create a service agreement for a project.

Before you create a service agreement, you might want to create service objects, service tasks, and service object groups that you can assign to a service agreement. By setting up service objects, tasks, and groups, you can create service agreements more efficiently. For more information about how to set up service objects, see [Create service objects](create-service-objects.md). For more information about how to set up service tasks, see [Create service tasks](create-service-tasks.md).

1.  Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**. On the **Action Pane**, in the **New** group, click **Service agreement**.
    
    –or–
    
    Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select a project in the list. On the **Action Pane**, on the **Manage** tab, click **Service** \> **Service agreement**.

2.  In the **Service agreements** form, on the **Service agreement** FastTab, enter a brief description for the service agreement. In the **Project ID** field, select a project for the service agreement. The customer information is automatically added from the selected project.
    

    > [!NOTE]
    > <P>If you create a service agreement from a project, the project identifier is automatically entered in the service agreement.</P>



3.  In the **Service agreement group** field, select a service agreement group. You can use the service agreement group to sort and organize service agreements.

4.  Select the **Continuous service** check box if the service period is longer than three months. The continuous service status determines the calculation of the service tax for the service agreement.

5.  In the **Service event group** field, select an event group.
    

    > [!NOTE]
    > <P>The <STRONG>Service event group</STRONG> field is available only if you select the <STRONG>Continuous service</STRONG> check box.</P>



6.  Complete the remaining information on the **Service agreement** FastTab. For more information, see [Service agreements (form)](https://technet.microsoft.com/en-us/library/aa617823\(v=ax.60\)).

7.  On the **Lines** FastTab, click **Add**, and then select a project transaction type for the service agreement. You can select an **Hour**, **Expense**, **Item**, or **Fee** type. The details that you can select for the line are determined by the type. For example, if you select an **Item** transaction type, you must also select an item number.

8.  On the **Line details** FastTab, on the **Prices** tab, enter the number of hours or the quantity of an item. The cost and sales information is automatically added for the selected transaction type. You cannot modify the cost and sales information in this form.

9.  Optional: You can copy lines from another service agreement or a service template. On the **Action Pane**, on the **Service agreement** tab, in the **Copy** group, click **Template lines** or **Agreement lines**.
    
    If you copy lines into the service agreement from another service agreement, you can specify whether you also copy service object and service task relations. If you copy these relations, they are added to any existing relations on the service agreement. If you copy service agreement lines from a service template, the service object and service task relations are automatically copied as service object relations and service task relations on the new service agreement lines.

## See also

[About service agreements](about-service-agreements.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

