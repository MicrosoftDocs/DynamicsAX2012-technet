---
title: ProductCompositionInformation.VariantInformation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: VariantInformation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCompositionInformation.VariantInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcompositioninformation.variantinformation(v=AX.60)
ms:contentKeyID: 62209559
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCompositionInformation.VariantInformation
dev_langs:
- CSharp
- C++
- VB
---

# VariantInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the properties associated with the variants of this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property VariantInformation As ProductVariantInformation
    Get
    Set
'Usage
Dim instance As ProductCompositionInformation
Dim value As ProductVariantInformation

value = instance.VariantInformation

instance.VariantInformation = value
```

``` csharp
[DataMemberAttribute]
public ProductVariantInformation VariantInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductVariantInformation^ VariantInformation {
    ProductVariantInformation^ get ();
    void set (ProductVariantInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductVariantInformation](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductCompositionInformation Class](productcompositioninformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

