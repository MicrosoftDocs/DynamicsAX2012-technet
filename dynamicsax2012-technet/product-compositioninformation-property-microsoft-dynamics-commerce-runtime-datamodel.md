---
title: Product.CompositionInformation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompositionInformation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.CompositionInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product.compositioninformation(v=AX.60)
ms:contentKeyID: 62208761
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product.CompositionInformation
dev_langs:
- CSharp
- C++
- VB
---

# CompositionInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the properties associated with the variants or kit components of this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CompositionInformation As ProductCompositionInformation
    Get
    Set
'Usage
Dim instance As Product
Dim value As ProductCompositionInformation

value = instance.CompositionInformation

instance.CompositionInformation = value
```

``` csharp
[DataMemberAttribute]
public ProductCompositionInformation CompositionInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductCompositionInformation^ CompositionInformation {
    ProductCompositionInformation^ get ();
    void set (ProductCompositionInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCompositionInformation](productcompositioninformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductCompositionInformation](productcompositioninformation-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Product Class](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

