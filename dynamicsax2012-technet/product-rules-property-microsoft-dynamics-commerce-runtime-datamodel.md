---
title: Product.Rules Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Rules Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Rules
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.rules(v=AX.60)
ms:contentKeyID: 62212127
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.Rules
dev_langs:
- CSharp
- C++
- VB
---

# Rules Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the object representing the rules governing the behavior of this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Rules As ProductRules
    Get
    Set
'Usage
Dim instance As Product
Dim value As ProductRules

value = instance.Rules

instance.Rules = value
```

``` csharp
[DataMemberAttribute]
public ProductRules Rules { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductRules^ Rules {
    ProductRules^ get ();
    void set (ProductRules^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductRules](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

