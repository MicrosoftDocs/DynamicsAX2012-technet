---
title: About service objects
TOCTitle: About service objects
ms:assetid: cebb2b96-f489-46c5-8149-b282934264f6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa572704(v=AX.60)
ms:contentKeyID: 37832535
ms.date: 07/29/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About service objects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Service objects are a customer’s assets and products for which you can perform a service. Depending on the type of service you provide, objects can be tangible or intangible:

  - Tangible objects are things, such as a machine or a building, on which you can perform a physical service task.
    
    A tangible service object can also be an inventory item that you create in the **Released product details** form. Depending on the inventory dimension group that you attach to the item, you can create a service object to a level of detail that includes the item serial number. This is useful when you must keep track of the exact item that the service object represents. For more information, see [About inventory dimensions and dimension groups](about-inventory-dimensions-and-dimension-groups.md).
    
    A tangible service object can also be an item that is not directly related to a company's direct production or supply chain. For example, a tool kit that is used for repairs in a service order can be a service object that is not included in inventory. In this case, you don’t register it as an inventory item.

  - Intangible objects are nonphysical things, such as a set of accounts or a legal document, on which you can perform a service task.
    
    **Example of an intangible service object**
    
    Company A maintains the financial records for several small companies. One of Company A's clients is the local football team, for which Company A does the weekly bookkeeping and annual audit of the club's accounts. The club's accounts are set up in the **Service objects** form and specified as the object in the service agreement. There are two service agreement lines for the object. Line 1 is weekly bookkeeping with a weekly interval assigned to the line, and line 2 is the annual audit with a yearly interval assigned to it.

## See also

[About service object relations](about-service-object-relations.md)

[Create service objects](create-service-objects.md)

[Service objects (form)](https://technet.microsoft.com/en-us/library/aa615497\(v=ax.60\))

  


