---
title: PagingInfo.NoPagination Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NoPagination Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.NoPagination
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.nopagination(v=AX.60)
ms:contentKeyID: 65317615
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.NoPagination
dev_langs:
- CSharp
- C++
- VB
---

# NoPagination Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a PagingInfo object that represents a non-paged request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property NoPagination As PagingInfo
    Get
'Usage
Dim value As PagingInfo

value = PagingInfo.NoPagination
```

``` csharp
public static PagingInfo NoPagination { get; }
```

``` c++
public:
static property PagingInfo^ NoPagination {
    PagingInfo^ get ();
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

