---
title: ProductRefiner.DataType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.DataType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefiner.datatype(v=AX.60)
ms:contentKeyID: 65319624
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner.DataType
dev_langs:
- CSharp
- C++
- VB
---

# DataType Property

Gets or sets the type of the property.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("DATATYPE")> _
Public Property DataType As AttributeDataType
    Get
    Set
'Usage
Dim instance As ProductRefiner
Dim value As AttributeDataType

value = instance.DataType

instance.DataType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("DATATYPE")]
public AttributeDataType DataType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"DATATYPE")]
public:
property AttributeDataType DataType {
    AttributeDataType get ();
    void set (AttributeDataType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType](attributedatatype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the property.  

## See Also

#### Reference

[ProductRefiner Class](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

