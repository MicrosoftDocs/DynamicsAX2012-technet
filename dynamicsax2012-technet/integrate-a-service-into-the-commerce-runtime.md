---
title: Integrate a Service into the Commerce Runtime
TOCTitle: Integrate a Service into the Commerce Runtime
ms:assetid: abd7fca1-a4d8-42bf-8a50-a974e8f2828b
ms:mtpsurl: https://technet.microsoft.com/library/JJ916619(v=AX.60)
ms:contentKeyID: 50934009
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Integrate a Service into the Commerce Runtime 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The commerce runtime includes several services that represent particular areas of functionality for your online store. If one of these services does not meet the needs of your store, you can completely replace it with your own service and continue to use the other services that are installed with the commerce runtime. This topic describes how to create a new service and add it to the commerce runtime configuration. For a complete walkthrough about how to integrate a third party shipping service, see [Walkthrough: Integrating a new Shipping Service](walkthrough-integrating-a-new-shipping-service.md).

## Creating a Service

A service handles any number of service messages. A service message is the combination of a service request and response. To create a service, implement a request, a response, and a service.

### To create a request object

1.  Create a class that inherits from the [ServiceRequest](https://technet.microsoft.com/library/jj760475\(v=ax.60\)) class.
    

    > [!NOTE]
    > <P>The ServiceRequest class encapsulates a service request that is sent to services. It exposes information about the context and operation context, which allows you to use logging and diagnostics functionality. It also exposes the Validate method that allows you to validate that the parameters that are passed in are valid. It also exposes the ServiceRequest constructor, which takes in the RequestContext object. The RequestContext object has information about the current request that is being executed.</P>



2.  Implement the ServiceRequest contructor.

3.  Optionally implement any validation that you want to perform on the request.

### To create a response object

1.  Create an object that inherits from the [ServiceResponse](https://technet.microsoft.com/library/jj762670\(v=ax.60\)) class.

2.  Implement code to perform your desired functionality. Typically, this would be a get or set operation.

### To create a service object

1.  Create an object that implements the [IService](https://technet.microsoft.com/library/jj762665\(v=ax.60\)) interface.

2.  Implement an execute method that takes a request object and returns a class that is a service response.

3.  Cast the request as a type the service can handle. If the cast succeeds, call a method to perform an action.

4.  Return a response.

## Modifying the Runtime Configuration File

Services are enumerated as types in the the commerce runtime config file. The commerce runtime config file controls which types to load. Services are loaded in the order in which they are listed in the configuration file. All of the default services are loaded automatically, but if you add a new service above one of the default services, the new service will replace the default service.


> [!NOTE]
> <P>You can also programmatically add a service to the catalog using the .NET API.</P>



### To modify the commerce runtime config file

1.  Open commerceRuntime.config in your solution.
    

    > [!NOTE]
    > <P>The location of this file varies based on your deployment. If you are customizing the SharePoint starter store, you can find the file by using the Internet Information Services (IIS) Manager. In IIS Manager, find the starter store under the <STRONG>Sites</STRONG> node. Right-click the public starter store, and then click <STRONG>Explore</STRONG>.</P>



2.  Add a line to include your new service. To load an entire assembly, add a line like the following example from [Walkthrough: Integrating a new Shipping Service](walkthrough-integrating-a-new-shipping-service.md):
    
        <add source="assembly" value="ContosoShippingCarrier, Version=1.0.0.0, Culture=neutral, PublicKeyToken=6598494e9dab8361, processorArchitecture=MSIL" />
    
    To add a specific type, add a line like the following:
    
        <add source="type" value="Fully_Qualified_Name_Of_Type, AssemblyName"/>

## See also

[Online Store](online-store.md)

[Retail Modern Point of Sale](retail-modern-point-of-sale.md)

  


