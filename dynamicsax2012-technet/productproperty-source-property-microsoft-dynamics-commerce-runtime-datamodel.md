---
title: ProductProperty.Source Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Source Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Source
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.source(v=AX.60)
ms:contentKeyID: 65316269
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Source
dev_langs:
- CSharp
- C++
- VB
---

# Source Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SOURCE")> _
Public Property Source As ProductAttributeValueSource
    Get
    Friend Set
'Usage
Dim instance As ProductProperty
Dim value As ProductAttributeValueSource

value = instance.Source
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SOURCE")]
public ProductAttributeValueSource Source { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SOURCE")]
public:
property ProductAttributeValueSource Source {
    ProductAttributeValueSource get ();
    internal: void set (ProductAttributeValueSource value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeValueSource](productattributevaluesource-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

