---
title: ProductProperty.Distance Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Distance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Distance
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.distance(v=AX.60)
ms:contentKeyID: 65319035
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Distance
dev_langs:
- CSharp
- C++
- VB
---

# Distance Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISTANCE")> _
<DataMemberAttribute> _
Public Property Distance As Integer
    Get
    Friend Set
'Usage
Dim instance As ProductProperty
Dim value As Integer

value = instance.Distance
```

``` csharp
[ColumnAttribute("DISTANCE")]
[DataMemberAttribute]
public int Distance { get; internal set; }
```

``` c++
[ColumnAttribute(L"DISTANCE")]
[DataMemberAttribute]
public:
property int Distance {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

