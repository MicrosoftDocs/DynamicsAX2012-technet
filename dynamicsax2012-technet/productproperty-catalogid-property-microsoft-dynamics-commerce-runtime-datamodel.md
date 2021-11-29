---
title: ProductProperty.CatalogId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.CatalogId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.catalogid(v=AX.60)
ms:contentKeyID: 65319451
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.CatalogId
dev_langs:
- CSharp
- C++
- VB
---

# CatalogId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CATALOG")> _
Public Property CatalogId As Long
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Long

value = instance.CatalogId

instance.CatalogId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CATALOG")]
public long CatalogId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CATALOG")]
public:
property long long CatalogId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

