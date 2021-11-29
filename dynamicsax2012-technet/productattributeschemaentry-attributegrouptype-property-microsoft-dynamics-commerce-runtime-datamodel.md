---
title: ProductAttributeSchemaEntry.AttributeGroupType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeGroupType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.AttributeGroupType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.attributegrouptype(v=AX.60)
ms:contentKeyID: 65318826
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.AttributeGroupType
dev_langs:
- CSharp
- C++
- VB
---

# AttributeGroupType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the attribute group type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ATTRIBUTEGROUPTYPE")> _
<DataMemberAttribute> _
Public Property AttributeGroupType As AttributeGroupType
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As AttributeGroupType

value = instance.AttributeGroupType

instance.AttributeGroupType = value
```

``` csharp
[ColumnAttribute("ATTRIBUTEGROUPTYPE")]
[DataMemberAttribute]
public AttributeGroupType AttributeGroupType { get; set; }
```

``` c++
[ColumnAttribute(L"ATTRIBUTEGROUPTYPE")]
[DataMemberAttribute]
public:
property AttributeGroupType AttributeGroupType {
    AttributeGroupType get ();
    void set (AttributeGroupType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroupType](attributegrouptype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeGroupType](attributegrouptype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

