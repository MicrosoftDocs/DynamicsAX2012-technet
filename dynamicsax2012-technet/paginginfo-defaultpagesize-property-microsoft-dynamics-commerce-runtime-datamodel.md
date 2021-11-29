---
title: PagingInfo.DefaultPageSize Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultPageSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.DefaultPageSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.defaultpagesize(v=AX.60)
ms:contentKeyID: 65319339
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.DefaultPageSize
dev_langs:
- CSharp
- C++
- VB
---

# DefaultPageSize Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the default number of records retrieved if no page size has been specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property DefaultPageSize As Integer
    Get
'Usage
Dim value As Integer

value = PagingInfo.DefaultPageSize
```

``` csharp
public static int DefaultPageSize { get; }
```

``` c++
public:
static property int DefaultPageSize {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

