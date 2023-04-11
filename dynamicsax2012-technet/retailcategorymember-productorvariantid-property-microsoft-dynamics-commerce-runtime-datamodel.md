---
title: RetailCategoryMember.ProductOrVariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductOrVariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailCategoryMember.ProductOrVariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retailcategorymember.productorvariantid(v=AX.60)
ms:contentKeyID: 62205725
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailCategoryMember.ProductOrVariantId
dev_langs:
- CSharp
- C++
- VB
---

# ProductOrVariantId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the product or variant ID specified on this discount line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PRODUCT")> _
<DataMemberAttribute> _
Public Property ProductOrVariantId As Long
    Get
    Set
'Usage
Dim instance As RetailCategoryMember
Dim value As Long

value = instance.ProductOrVariantId

instance.ProductOrVariantId = value
```

``` csharp
[ColumnAttribute("PRODUCT")]
[DataMemberAttribute]
public long ProductOrVariantId { get; set; }
```

``` c++
[ColumnAttribute(L"PRODUCT")]
[DataMemberAttribute]
public:
property long long ProductOrVariantId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[RetailCategoryMember Class](retailcategorymember-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

