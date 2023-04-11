---
title: KitComponent.KitLineProductId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineProductId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.KitLineProductId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponent.kitlineproductid(v=AX.60)
ms:contentKeyID: 62213353
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.KitLineProductId
dev_langs:
- CSharp
- C++
- VB
---

# KitLineProductId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the productId of the product used in a kit as a component or substitute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KITLINEPRODUCTLISTING")> _
<DataMemberAttribute> _
Public Property KitLineProductId As Long
    Get
    Friend Set
'Usage
Dim instance As KitComponent
Dim value As Long

value = instance.KitLineProductId
```

``` csharp
[ColumnAttribute("KITLINEPRODUCTLISTING")]
[DataMemberAttribute]
public long KitLineProductId { get; internal set; }
```

``` c++
[ColumnAttribute(L"KITLINEPRODUCTLISTING")]
[DataMemberAttribute]
public:
property long long KitLineProductId {
    long long get ();
    internal: void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitComponent Class](kitcomponent-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

