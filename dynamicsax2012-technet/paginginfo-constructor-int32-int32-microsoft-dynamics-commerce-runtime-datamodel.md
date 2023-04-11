---
title: PagingInfo Constructor (Int32, Int32) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PagingInfo Constructor (Int32, Int32)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.#ctor(System.Int32,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.paginginfo(v=AX.60)
ms:contentKeyID: 65316371
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PagingInfo Constructor (Int32, Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    top As Integer, _
    skip As Integer _
)
'Usage
Dim top As Integer
Dim skip As Integer

Dim instance As New PagingInfo(top, skip)
```

``` csharp
public PagingInfo(
    int top,
    int skip
)
```

``` c++
public:
PagingInfo(
    int top, 
    int skip
)
```

#### Parameters

  - top  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - skip  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[PagingInfo Overload](paginginfo-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

