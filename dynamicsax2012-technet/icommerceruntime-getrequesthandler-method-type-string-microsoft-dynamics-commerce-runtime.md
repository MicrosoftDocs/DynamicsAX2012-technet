---
title: ICommerceRuntime.GetRequestHandler Method (Type, String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandler Method (Type, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.GetRequestHandler(System.Type,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntime.getrequesthandler(v=AX.60)
ms:contentKeyID: 65322199
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRequestHandler Method (Type, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets all request handler that support the requestType request type by name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetRequestHandler ( _
    requestType As Type, _
    handlerName As String _
) As IRequestHandler
'Usage
Dim instance As ICommerceRuntime
Dim requestType As Type
Dim handlerName As String
Dim returnValue As IRequestHandler

returnValue = instance.GetRequestHandler(requestType, _
    handlerName)
```

``` csharp
IRequestHandler GetRequestHandler(
    Type requestType,
    string handlerName
)
```

``` c++
IRequestHandler^ GetRequestHandler(
    Type^ requestType, 
    String^ handlerName
)
```

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - handlerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Workflow.IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)  
The matching request handlers.  

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[GetRequestHandler Overload](icommerceruntime-getrequesthandler-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

