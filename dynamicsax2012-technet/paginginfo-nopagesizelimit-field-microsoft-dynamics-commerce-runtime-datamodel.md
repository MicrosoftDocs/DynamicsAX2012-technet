---
title: PagingInfo.NoPageSizeLimit Field (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NoPageSizeLimit Field
ms:assetid: F:Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.NoPageSizeLimit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paginginfo.nopagesizelimit(v=AX.60)
ms:contentKeyID: 65317366
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PagingInfo.NoPageSizeLimit
dev_langs:
- CSharp
- C++
- VB
---

# NoPageSizeLimit Field


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates that no page size limit is to be enforced.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly NoPageSizeLimit As Integer
'Usage
Dim value As Integer

value = PagingInfo.NoPageSizeLimit
```

``` csharp
public static readonly int NoPageSizeLimit
```

``` c++
public:
static initonly int NoPageSizeLimit
```

## Remarks

This should be used sparingly and only in circumstances where the amount of data retrieved is logically minimal.

## See Also

#### Reference

[PagingInfo Class](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

