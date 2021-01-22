---
title: CatalogPriceGroup.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogPriceGroup.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.catalogpricegroup.catalogid(v=AX.60)
ms:contentKeyID: 62213842
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CatalogPriceGroup.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property

Gets the price group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATALOGID")> _
Public Property CatalogId As Long
    Get
    Friend Set
'Usage
Dim instance As CatalogPriceGroup
Dim value As Long

value = instance.CatalogId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATALOGID")]
public long CatalogId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATALOGID")]
public:
property long long CatalogId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[CatalogPriceGroup Class](catalogpricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

