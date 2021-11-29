---
title: SalesLine.CatalogIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.CatalogIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.catalogids(v=AX.60)
ms:contentKeyID: 62214061
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.CatalogIds
dev_langs:
- CSharp
- C++
- VB
---

# CatalogIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the active catalogs the product is included in.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property CatalogIds As ISet(Of Long)
    Get
    Friend Set
'Usage
Dim instance As SalesLine
Dim value As ISet(Of Long)

value = instance.CatalogIds
```

``` csharp
public ISet<long> CatalogIds { get; internal set; }
```

``` c++
public:
property ISet<long long>^ CatalogIds {
    ISet<long long>^ get ();
    internal: void set (ISet<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ISet\<T\>](https://technet.microsoft.com/library/dd412081\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

