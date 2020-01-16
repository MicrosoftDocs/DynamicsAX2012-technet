---
title: AttributeProduct.RelationTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RelationTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.RelationTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributeproduct.relationtypevalue(v=AX.60)
ms:contentKeyID: 65318544
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.RelationTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# RelationTypeValue Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RelationTypeValue As Integer
    Get
    Friend Set
'Usage
Dim instance As AttributeProduct
Dim value As Integer

value = instance.RelationTypeValue
```

``` csharp
[DataMemberAttribute]
public int RelationTypeValue { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property int RelationTypeValue {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[AttributeProduct Class](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

