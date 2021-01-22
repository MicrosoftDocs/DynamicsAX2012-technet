---
title: CommerceRuntime.GetRequestHandlers Method (Type, String) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandlers Method (Type, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetRequestHandlers(System.Type,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.getrequesthandlers(v=AX.60)
ms:contentKeyID: 65321182
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRequestHandlers Method (Type, String)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function GetRequestHandlers ( _
    requestType As Type, _
    handlerName As String _
) As IEnumerable(Of IRequestHandler)
'Usage
Dim instance As CommerceRuntime
Dim requestType As Type
Dim handlerName As String
Dim returnValue As IEnumerable(Of IRequestHandler)

returnValue = instance.GetRequestHandlers(requestType, _
    handlerName)
```

``` csharp
public IEnumerable<IRequestHandler> GetRequestHandlers(
    Type requestType,
    string handlerName
)
```

``` c++
public:
virtual IEnumerable<IRequestHandler^>^ GetRequestHandlers(
    Type^ requestType, 
    String^ handlerName
) sealed
```

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - handlerName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)\>  

#### Implements

[ICommerceRuntime.GetRequestHandlers(Type, String)](icommerceruntime-getrequesthandlers-method-type-string-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[GetRequestHandlers Overload](commerceruntime-getrequesthandlers-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

