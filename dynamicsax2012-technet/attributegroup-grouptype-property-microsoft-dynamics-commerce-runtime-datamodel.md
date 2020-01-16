---
title: AttributeGroup.GroupType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GroupType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroup.GroupType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributegroup.grouptype(v=AX.60)
ms:contentKeyID: 49832785
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroup.GroupType
dev_langs:
- CSharp
- C++
- VB
---

# GroupType Property

Gets or sets the group type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ATTRIBUTEGROUPTYPE")> _
<DataMemberAttribute> _
Public Property GroupType As AttributeGroupType
    Get
    Set
'Usage
Dim instance As AttributeGroup
Dim value As AttributeGroupType

value = instance.GroupType

instance.GroupType = value
```

``` csharp
[ColumnAttribute("ATTRIBUTEGROUPTYPE")]
[DataMemberAttribute]
public AttributeGroupType GroupType { get; set; }
```

``` c++
[ColumnAttribute(L"ATTRIBUTEGROUPTYPE")]
[DataMemberAttribute]
public:
property AttributeGroupType GroupType {
    AttributeGroupType get ();
    void set (AttributeGroupType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroupType](attributegrouptype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The group type.  

## See Also

#### Reference

[AttributeGroup Class](attributegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

