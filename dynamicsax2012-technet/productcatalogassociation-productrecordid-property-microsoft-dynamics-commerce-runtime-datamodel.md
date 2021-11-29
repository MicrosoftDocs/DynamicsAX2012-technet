---
title: ProductCatalogAssociation.ProductRecordId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductRecordId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation.ProductRecordId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalogassociation.productrecordid(v=AX.60)
ms:contentKeyID: 62209790
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalogAssociation.ProductRecordId
dev_langs:
- CSharp
- C++
- VB
---

# ProductRecordId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product record identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PRODUCT")> _
Public Property ProductRecordId As Long
    Get
    Friend Set
'Usage
Dim instance As ProductCatalogAssociation
Dim value As Long

value = instance.ProductRecordId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PRODUCT")]
public long ProductRecordId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PRODUCT")]
public:
property long long ProductRecordId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductCatalogAssociation Class](productcatalogassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

