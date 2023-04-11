---
title: ProductProperty.IsDimensionProperty Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDimensionProperty Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.IsDimensionProperty
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.isdimensionproperty(v=AX.60)
ms:contentKeyID: 62209633
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.IsDimensionProperty
dev_langs:
- CSharp
- C++
- VB
---

# IsDimensionProperty Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether this property is a product dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsDimensionProperty As Boolean
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Boolean

value = instance.IsDimensionProperty

instance.IsDimensionProperty = value
```

``` csharp
[DataMemberAttribute]
public bool IsDimensionProperty { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsDimensionProperty {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

