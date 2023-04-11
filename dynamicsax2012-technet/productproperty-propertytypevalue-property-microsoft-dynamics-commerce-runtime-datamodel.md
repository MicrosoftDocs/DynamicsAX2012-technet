---
title: ProductProperty.PropertyTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PropertyTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.PropertyTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.propertytypevalue(v=AX.60)
ms:contentKeyID: 62212753
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.PropertyTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# PropertyTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the AttributeDataType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PropertyTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Integer

value = instance.PropertyTypeValue

instance.PropertyTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int PropertyTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int PropertyTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

