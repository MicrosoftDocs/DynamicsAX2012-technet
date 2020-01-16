---
title: Consuming External Web Services
TOCTitle: Consuming External Web Services
ms:assetid: 69eecc2b-3306-4028-9069-4dca8fdccb0c
ms:mtpsurl: https://technet.microsoft.com/library/Hh500187(v=AX.60)
ms:contentKeyID: 37820254
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Consuming External Web Services 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX programmability model supports services. This means you can consume web services from X++ code, making external functionality available in your Microsoft Dynamics AX application. Some web services are provided free of charge, while others have licensing models that require you to pay a fee. In Microsoft Dynamics AX external web services can enable the following scenarios:

  - Accessing currency exchange rates.

  - Getting shipping rates from multiple carriers.

  - Retrieving availability of parts from external suppliers.

  - Calculating local tax values.

To consume an external web service, you must first create a service reference for it in a Microsoft Visual Studio project, and then add it to the AOT using Visual Studio Tools. After creating a reference to the external web service, you can write code to invoke it from X++ and see the available methods with IntelliSense.

## Calling an External Web Service from X++

After you have added the service reference in Visual Studio, you can call the external web service from Microsoft Dynamics AX using X++ or C\#. For example, you can use the [Bing™ Search and Map APIs](http://www.bing.com/toolbox/bingdeveloper/) in your Microsoft Dynamics AX applications.The following topic illustrates adding the Bing Search service reference and calling it from a job in Microsoft Dynamics AX.

  - [Walkthrough: Calling an External Web Service from X++](walkthrough-calling-an-external-web-service-from-x.md)

## See also

[Install Visual Studio Tools](install-visual-studio-tools.md)

