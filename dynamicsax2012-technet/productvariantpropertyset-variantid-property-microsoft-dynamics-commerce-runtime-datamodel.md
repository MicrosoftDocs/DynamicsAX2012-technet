---
title: ProductVariantPropertySet.VariantId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertySet.VariantId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantpropertyset.variantid(v=AX.60)
ms:contentKeyID: 62205734
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantPropertySet.VariantId
dev_langs:
- CSharp
- C++
- VB
---

# VariantId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the variant identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property VariantId As Long
    Get
    Set
'Usage
Dim instance As ProductVariantPropertySet
Dim value As Long

value = instance.VariantId

instance.VariantId = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public long VariantId { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property long long VariantId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariantPropertySet Class](productvariantpropertyset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

