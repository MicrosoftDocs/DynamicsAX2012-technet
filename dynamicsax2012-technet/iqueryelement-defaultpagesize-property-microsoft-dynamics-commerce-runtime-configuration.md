---
title: IQueryElement.DefaultPageSize Property  (Microsoft.Dynamics.Commerce.Runtime.Configuration)
TOCTitle: DefaultPageSize Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Configuration.IQueryElement.DefaultPageSize
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.configuration.iqueryelement.defaultpagesize(v=AX.60)
ms:contentKeyID: 65321033
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Configuration.IQueryElement.DefaultPageSize
dev_langs:
- CSharp
- C++
- VB
---

# DefaultPageSize Property

Gets the default page size for the [PagingInfo](paginginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Configuration](microsoft-dynamics-commerce-runtime-configuration-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property DefaultPageSize As Integer
    Get
'Usage
Dim instance As IQueryElement
Dim value As Integer

value = instance.DefaultPageSize
```

``` csharp
int DefaultPageSize { get; }
```

``` c++
property int DefaultPageSize {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## Remarks

The value used when no page size has been explicitly specified for the query.

## See Also

#### Reference

[IQueryElement Interface](iqueryelement-interface-microsoft-dynamics-commerce-runtime-configuration.md)

[Microsoft.Dynamics.Commerce.Runtime.Configuration Namespace](microsoft-dynamics-commerce-runtime-configuration-namespace.md)

