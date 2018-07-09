---
title: View service object relations
TOCTitle: View service object relations
ms:assetid: ff78927b-6072-4fee-a9fc-8cc265b58a19
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh299240(v=AX.60)
ms:contentKeyID: 36384346
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- EPServiceObjectRelationInfo
- EPServiceObjectRelationList
---

# View service object relations [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Service object relations** page to view a list of the service object relations that have been created for a service agreement or order. You can then use the **Service object** page to view the details of the service object that is associated with the service object relation.

Service objects are the general objects that you can perform a service on. For example, you might perform repair tasks for machinery or buildings, or consultant tasks for a set of accounts or for a legal document.

A service object relation is the specific object of the service. It is used to associate a service object with a service agreement or service order. This relationship is set up when a service object relation is created for a service agreement or order, and then service objects are added to the service object relation. When you add a service object relation to a service agreement or order, the service object can be associated to the service agreement or order lines. A template BOM can also be specified for a service object relation. This is a list of components for service object that are serviced regularly.


> [!NOTE]
> <P>These tasks are completed using the Microsoft Dynamics AX client.</P>



1.  Click **Service management** on the top link bar, and then click either **Service agreements** or **Service orders** on the Quick Launch. The **View service agreements** or **View service orders** page is displayed.
    
      - To view the service object relations for a service agreement, click a service agreement link. The **View service agreement** page is displayed. On the Action Pane, click **Service objects**.
    
      - To view the service object relations for a service order, select the service order, and then on the Action Pane, click **Service objects**.
    
    The **View service object relations** page is displayed, where you can view general service object relation information, such as the service object and the reference code that is used to identify the service object relation.

2.  To view details about the service object relation, select the line and then click the **Details** button. The details show whether the relation table type is service agreement or service order, the service order or service agreement number that the service object is associated with, and the template BOM that is used.

## See also

[About service agreements and service orders](about-service-agreements-and-service-orders.md)

[View service agreements](view-service-agreements.md)

[View service orders](view-service-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

