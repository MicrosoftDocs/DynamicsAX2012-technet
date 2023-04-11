---
title: ProductProperty.PropertyType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PropertyType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.PropertyType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.propertytype(v=AX.60)
ms:contentKeyID: 62205306
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.PropertyType
dev_langs:
- CSharp
- C++
- VB
---

# PropertyType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the property.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property PropertyType As ProductPropertyType
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As ProductPropertyType

value = instance.PropertyType

instance.PropertyType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public ProductPropertyType PropertyType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ProductPropertyType PropertyType {
    ProductPropertyType get ();
    void set (ProductPropertyType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertyType](productpropertytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The type of the property.  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

