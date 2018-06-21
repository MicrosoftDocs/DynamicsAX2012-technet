---
title: Commerce Runtime
TOCTitle: Commerce Runtime
ms:assetid: 5133ee05-ea77-438b-bf4d-4c9dc18bc45b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ916620(v=AX.60)
ms:contentKeyID: 50934011
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Commerce Runtime [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Microsoft Dynamics AX commerce runtime (CRT) serves as the engine for a retail channel. It connects to a CRT database that stores business data for the channel.

## Commerce Runtime Architecture

The following diagram shows the components of the CRT:

![Commerce Runtime](images/JJ916620.CRT_Overview(en-us,AX.60).jpg "Commerce Runtime")

### ![JJ916620.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ916620.collapse_all(en-us,AX.60).gif")Data access

On top of the database is a data access layer. In the data access layer, raw data is translated into objects in memory. For example, an object could be a product. Products have attributes like price and color. The data access layer has functions you can use to manipulate these objects. Stored procedures pass packets of data from the database to data entities that can be used in services and workflow. You can update the packets of data to include new fields that you add in Microsoft Dynamics AX. For more information, see [Customize the Data in a Commerce Entity](customize-the-data-in-a-commerce-entity.md).

### ![JJ916620.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ916620.collapse_all(en-us,AX.60).gif")Services

On top of the data access layer is a services layer. Services query for real time data. You can use these services to customize existing functionality or add your own service with new functionality. For more information about services, see [Services Overview for Commerce Runtime](services-overview-for-commerce-runtime.md).

### ![JJ916620.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ916620.collapse_all(en-us,AX.60).gif")Workflow

On top of the services layer is the workflow layer. A workflow is a collection of services and business logic that together define business processes. For example, when a customer adds an item to the cart, you could use workflow to get the price, perform validation, check inventory quantity, calculate shipping, calculate tax, and calculate discounts. You can utilize workflows that are included in Microsoft Dynamics AX, or you can create new workflows. You can even use a workflow to connect to a third party system as part of your business processes. For information about how to create workflows, see [Create Commerce Runtime Workflows](create-commerce-runtime-workflows.md).

### ![JJ916620.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ916620.collapse_all(en-us,AX.60).gif")Application Programming Interface (API)

On top of the workflow layer is the API layer. You can use the API for things like getting information about items, price calculation, shipping calculation, and placing orders. You can extend the API to fit your business processes. For more information, see the [.NET Framework Classes for Microsoft Dynamics AX Commerce Runtime](net-framework-classes-for-microsoft-dynamics-ax-commerce-runtime.md) reference documentation.

## See also

[Online Store](online-store.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

