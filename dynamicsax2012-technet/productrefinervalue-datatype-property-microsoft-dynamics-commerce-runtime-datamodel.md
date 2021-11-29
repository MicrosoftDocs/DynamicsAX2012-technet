---
title: ProductRefinerValue.DataType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.DataType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrefinervalue.datatype(v=AX.60)
ms:contentKeyID: 65320036
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue.DataType
dev_langs:
- CSharp
- C++
- VB
---

# DataType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the data type of the refiner value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATATYPE")> _
<IgnoreDataMemberAttribute> _
Public Property DataType As AttributeDataType
    Get
    Set
'Usage
Dim instance As ProductRefinerValue
Dim value As AttributeDataType

value = instance.DataType

instance.DataType = value
```

``` csharp
[ColumnAttribute("DATATYPE")]
[IgnoreDataMemberAttribute]
public AttributeDataType DataType { get; set; }
```

``` c++
[ColumnAttribute(L"DATATYPE")]
[IgnoreDataMemberAttribute]
public:
property AttributeDataType DataType {
    AttributeDataType get ();
    void set (AttributeDataType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeDataType](attributedatatype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The data type of the refiner value.  

## See Also

#### Reference

[ProductRefinerValue Class](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

