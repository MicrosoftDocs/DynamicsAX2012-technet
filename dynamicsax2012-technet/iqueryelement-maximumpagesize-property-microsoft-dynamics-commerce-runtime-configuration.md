---
title: IQueryElement.MaximumPageSize Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: MaximumPageSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.IQueryElement.MaximumPageSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.iqueryelement.maximumpagesize(v=AX.60)
ms:contentKeyID: 65316881
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.IQueryElement.MaximumPageSize
dev_langs:
- CSharp
- C++
- VB
---

# MaximumPageSize Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum page size for the [PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property MaximumPageSize As Integer
    Get
'Usage
Dim instance As IQueryElement
Dim value As Integer

value = instance.MaximumPageSize
```

``` csharp
int MaximumPageSize { get; }
```

``` c++
property int MaximumPageSize {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## Remarks

The largest value used regardless of what page size has been requested.

## See Also

#### Reference

[IQueryElement Interface](iqueryelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

