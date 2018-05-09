---
title: ProductAttributeSchemaEntry.DataType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.DataType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.datatype(v=AX.60)
ms:contentKeyID: 65321158
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.DataType
dev_langs:
- CSharp
- C++
- VB
---

# DataType Property

Gets or sets the data type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DATATYPE")> _
Public Property DataType As AttributeDataType
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As AttributeDataType

value = instance.DataType

instance.DataType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DATATYPE")]
public AttributeDataType DataType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DATATYPE")]
public:
property AttributeDataType DataType {
    AttributeDataType get ();
    void set (AttributeDataType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType](attributedatatype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeDataType](attributedatatype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

