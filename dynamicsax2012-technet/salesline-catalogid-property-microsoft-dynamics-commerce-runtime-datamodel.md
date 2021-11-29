---
title: SalesLine.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.catalogid(v=AX.60)
ms:contentKeyID: 62214373
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the catalog on item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATALOG")> _
<DataMemberAttribute> _
Public Property CatalogId As Long
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Long

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[ColumnAttribute("CATALOG")]
[DataMemberAttribute]
public long CatalogId { get; set; }
```

``` c++
[ColumnAttribute(L"CATALOG")]
[DataMemberAttribute]
public:
property long long CatalogId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

