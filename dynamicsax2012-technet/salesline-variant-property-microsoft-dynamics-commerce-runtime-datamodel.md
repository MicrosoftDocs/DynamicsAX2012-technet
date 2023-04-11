---
title: SalesLine.Variant Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Variant Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.Variant
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.variant(v=AX.60)
ms:contentKeyID: 49846750
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.Variant
dev_langs:
- CSharp
- C++
- VB
---

# Variant Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the variant values if this item is a variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VARIANT")> _
<IgnoreDataMemberAttribute> _
Public Property Variant As ProductVariant
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As ProductVariant

value = instance.Variant

instance.Variant = value
```

``` csharp
[ColumnAttribute("VARIANT")]
[IgnoreDataMemberAttribute]
public ProductVariant Variant { get; set; }
```

``` c++
[ColumnAttribute(L"VARIANT")]
[IgnoreDataMemberAttribute]
public:
property ProductVariant^ Variant {
    ProductVariant^ get ();
    void set (ProductVariant^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns Variant.  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

