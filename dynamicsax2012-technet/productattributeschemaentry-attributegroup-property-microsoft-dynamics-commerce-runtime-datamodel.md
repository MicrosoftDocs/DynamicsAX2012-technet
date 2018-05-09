---
title: ProductAttributeSchemaEntry.AttributeGroup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AttributeGroup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.AttributeGroup
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.attributegroup(v=AX.60)
ms:contentKeyID: 65322411
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.AttributeGroup
dev_langs:
- CSharp
- C++
- VB
---

# AttributeGroup Property

Gets or sets the attribute group.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ATTRIBUTEGROUP")> _
Public Property AttributeGroup As Long
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As Long

value = instance.AttributeGroup

instance.AttributeGroup = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ATTRIBUTEGROUP")]
public long AttributeGroup { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ATTRIBUTEGROUP")]
public:
property long long AttributeGroup {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

