---
title: ProductProperty.GroupTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GroupTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.grouptypevalue(v=AX.60)
ms:contentKeyID: 62208062
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.GroupTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# GroupTypeValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of the AttributeGroupType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GroupTypeValue As Integer
    Get
    Set
'Usage
Dim instance As ProductProperty
Dim value As Integer

value = instance.GroupTypeValue

instance.GroupTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int GroupTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int GroupTypeValue {
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

