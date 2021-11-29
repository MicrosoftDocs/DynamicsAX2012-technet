---
title: IOperationRequestHandler.SupportedOperationIds Property  (Microsoft.Dynamics.Commerce.Runtime.Handlers)
TOCTitle: SupportedOperationIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Handlers.IOperationRequestHandler.SupportedOperationIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.handlers.ioperationrequesthandler.supportedoperationids(v=AX.60)
ms:contentKeyID: 65319734
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Handlers.IOperationRequestHandler.SupportedOperationIds
dev_langs:
- CSharp
- C++
- VB
---

# SupportedOperationIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a collection of operation identifiers supported by this request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Handlers](microsoft-dynamics-commerce-runtime-handlers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SupportedOperationIds As IEnumerable(Of Integer)
    Get
'Usage
Dim instance As IOperationRequestHandler
Dim value As IEnumerable(Of Integer)

value = instance.SupportedOperationIds
```

``` csharp
IEnumerable<int> SupportedOperationIds { get; }
```

``` c++
property IEnumerable<int>^ SupportedOperationIds {
    IEnumerable<int>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[IOperationRequestHandler Interface](ioperationrequesthandler-interface-microsoft-dynamics-commerce-runtime-handlers.md)

[Microsoft.Dynamics.Commerce.Runtime.Handlers Namespace](microsoft-dynamics-commerce-runtime-handlers-namespace.md)

