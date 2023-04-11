---
title: ProductVariantInformation.ActiveVariantProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ActiveVariantProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.ActiveVariantProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.activevariantproductid(v=AX.60)
ms:contentKeyID: 62209711
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.ActiveVariantProductId
dev_langs:
- CSharp
- C++
- VB
---

# ActiveVariantProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the distinct product variant id of the variant which matches the input search criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ActiveVariantProductId As Long
    Get
    Set
'Usage
Dim instance As ProductVariantInformation
Dim value As Long

value = instance.ActiveVariantProductId

instance.ActiveVariantProductId = value
```

``` csharp
[DataMemberAttribute]
public long ActiveVariantProductId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ActiveVariantProductId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## Remarks

The Product APIs return complete products for a given input search criteria, and in certain cases, the exact variant which matched the criteria cannot be inferred by the client. In those cases, the CRT will set the ActiveVariant property to the id of the matching variant. This id is 0 in all other cases.

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

