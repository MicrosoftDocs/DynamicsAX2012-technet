---
title: ICommerceRuntime.GetRequestHandlers Method (Type, Int32) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandlers Method (Type, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.GetRequestHandlers(System.Type,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.icommerceruntime.getrequesthandlers(v=AX.60)
ms:contentKeyID: 65322214
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRequestHandlers Method (Type, Int32)

Gets all request handlers that support the requestType request type by operation identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetRequestHandlers ( _
    requestType As Type, _
    operationIdentifier As Integer _
) As IEnumerable(Of IRequestHandler)
'Usage
Dim instance As ICommerceRuntime
Dim requestType As Type
Dim operationIdentifier As Integer
Dim returnValue As IEnumerable(Of IRequestHandler)

returnValue = instance.GetRequestHandlers(requestType, _
    operationIdentifier)
```

``` csharp
IEnumerable<IRequestHandler> GetRequestHandlers(
    Type requestType,
    int operationIdentifier
)
```

``` c++
IEnumerable<IRequestHandler^>^ GetRequestHandlers(
    Type^ requestType, 
    int operationIdentifier
)
```

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/en-us/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - operationIdentifier  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)\>  
The matching request handlers.  

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[GetRequestHandlers Overload](icommerceruntime-getrequesthandlers-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

