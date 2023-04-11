---
title: CommerceRuntime.GetRequestHandlers(THandler) Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetRequestHandlers(THandler) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetRequestHandlers``1(System.Type)
ms:mtpsurl: https://technet.microsoft.com/library/Dn989498(v=AX.60)
ms:contentKeyID: 65319958
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.GetRequestHandlers``1
dev_langs:
- CSharp
- C++
- VB
---

# GetRequestHandlers(THandler) Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function GetRequestHandlers(Of THandler As IRequestHandler) ( _
    requestType As Type _
) As IEnumerable(Of THandler)
'Usage
Dim instance As CommerceRuntime
Dim requestType As Type
Dim returnValue As IEnumerable(Of THandler)

returnValue = instance.GetRequestHandlers(requestType)
```

``` csharp
public IEnumerable<THandler> GetRequestHandlers<THandler>(
    Type requestType
)
where THandler : IRequestHandler
```

``` c++
public:
generic<typename THandler>
where THandler : IRequestHandler
virtual IEnumerable<THandler>^ GetRequestHandlers(
    Type^ requestType
) sealed
```

#### Type Parameters

  - THandler

#### Parameters

  - requestType  
    Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<THandler\>  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

