---
title: AttributeBase.DataType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.DataType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.attributebase.datatype(v=AX.60)
ms:contentKeyID: 49853072
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeBase.DataType
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
<ColumnAttribute("DATATYPE")> _
<DataMemberAttribute> _
Public Property DataType As AttributeDataType
    Get
    Set
'Usage
Dim instance As AttributeBase
Dim value As AttributeDataType

value = instance.DataType

instance.DataType = value
```

``` csharp
[ColumnAttribute("DATATYPE")]
[DataMemberAttribute]
public AttributeDataType DataType { get; set; }
```

``` c++
[ColumnAttribute(L"DATATYPE")]
[DataMemberAttribute]
public:
property AttributeDataType DataType {
    AttributeDataType get ();
    void set (AttributeDataType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType](attributedatatype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The data type.  

## See Also

#### Reference

[AttributeBase Class](attributebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

