---
title: ProductCompositionInformation.KitDefinition Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitDefinition Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCompositionInformation.KitDefinition
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcompositioninformation.kitdefinition(v=AX.60)
ms:contentKeyID: 62208597
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCompositionInformation.KitDefinition
dev_langs:
- CSharp
- C++
- VB
---

# KitDefinition Property

Gets or sets the kit related properties associated with the variants of this product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitDefinition As KitDefinition
    Get
    Set
'Usage
Dim instance As ProductCompositionInformation
Dim value As KitDefinition

value = instance.KitDefinition

instance.KitDefinition = value
```

``` csharp
[DataMemberAttribute]
public KitDefinition KitDefinition { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property KitDefinition^ KitDefinition {
    KitDefinition^ get ();
    void set (KitDefinition^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.KitDefinition](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [KitDefinition](kitdefinition-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductCompositionInformation Class](productcompositioninformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

