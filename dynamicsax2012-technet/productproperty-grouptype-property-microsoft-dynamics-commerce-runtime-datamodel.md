---
title: ProductProperty.GroupType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GroupType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.grouptype(v=AX.60)
ms:contentKeyID: 62206030
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupType
dev_langs:
- CSharp
- C++
- VB
---

# GroupType Property

Gets the underlying attribute's group type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property GroupType As AttributeGroupType
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As AttributeGroupType

value = instance.GroupType

instance.GroupType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public AttributeGroupType GroupType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property AttributeGroupType GroupType {
    AttributeGroupType get ();
    void set (AttributeGroupType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeGroupType](attributegrouptype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AttributeGroupType](attributegrouptype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

