---
title: AttributeProduct.RelationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RelationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.RelationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributeproduct.relationtype(v=AX.60)
ms:contentKeyID: 49851138
author: tonyafehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.RelationType
dev_langs:
- CSharp
- C++
- VB
---

# RelationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the relation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RELATIONTYPE")> _
<IgnoreDataMemberAttribute> _
Public Property RelationType As ProductAttributeRelationType
    Get
    Friend Set
'Usage
Dim instance As AttributeProduct
Dim value As ProductAttributeRelationType

value = instance.RelationType
```

``` csharp
[ColumnAttribute("RELATIONTYPE")]
[IgnoreDataMemberAttribute]
public ProductAttributeRelationType RelationType { get; internal set; }
```

``` c++
[ColumnAttribute(L"RELATIONTYPE")]
[IgnoreDataMemberAttribute]
public:
property ProductAttributeRelationType RelationType {
    ProductAttributeRelationType get ();
    internal: void set (ProductAttributeRelationType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeRelationType](productattributerelationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductAttributeRelationType](productattributerelationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[AttributeProduct Class](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

