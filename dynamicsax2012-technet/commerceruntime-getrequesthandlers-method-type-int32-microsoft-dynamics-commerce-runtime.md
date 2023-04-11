---
title: CommerceRuntime.GetRequestHandlers Method (Type, Int32) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandlers Method (Type, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetRequestHandlers(System.Type,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.getrequesthandlers(v=AX.60)
ms:contentKeyID: 65316163
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetRequestHandlers Method (Type, Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function GetRequestHandlers ( _
    requestType As Type, _
    operationIdentifier As Integer _
) As IEnumerable(Of IRequestHandler)
'Usage
Dim instance As CommerceRuntime
Dim requestType As Type
Dim operationIdentifier As Integer
Dim returnValue As IEnumerable(Of IRequestHandler)

returnValue = instance.GetRequestHandlers(requestType, _
    operationIdentifier)
```

``` csharp
public IEnumerable<IRequestHandler> GetRequestHandlers(
    Type requestType,
    int operationIdentifier
)
```

``` c++
public:
virtual IEnumerable<IRequestHandler^>^ GetRequestHandlers(
    Type^ requestType, 
    int operationIdentifier
) sealed
```

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

<!-- end list -->

  - operationIdentifier  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[IRequestHandler](irequesthandler-interface-microsoft-dynamics-commerce-runtime-workflow.md)\>  

#### Implements

[ICommerceRuntime.GetRequestHandlers(Type, Int32)](icommerceruntime-getrequesthandlers-method-type-int32-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[GetRequestHandlers Overload](commerceruntime-getrequesthandlers-method-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

