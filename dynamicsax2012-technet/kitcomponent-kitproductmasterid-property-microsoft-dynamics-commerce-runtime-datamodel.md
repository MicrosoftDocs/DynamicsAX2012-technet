---
title: KitComponent.KitProductMasterId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitProductMasterId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.KitProductMasterId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponent.kitproductmasterid(v=AX.60)
ms:contentKeyID: 62208072
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.KitProductMasterId
dev_langs:
- CSharp
- C++
- VB
---

# KitProductMasterId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Kit's ProductMasterId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KITPRODUCTMASTERLISTING")> _
<DataMemberAttribute> _
Public Property KitProductMasterId As Long
    Get
    Friend Set
'Usage
Dim instance As KitComponent
Dim value As Long

value = instance.KitProductMasterId
```

``` csharp
[ColumnAttribute("KITPRODUCTMASTERLISTING")]
[DataMemberAttribute]
public long KitProductMasterId { get; internal set; }
```

``` c++
[ColumnAttribute(L"KITPRODUCTMASTERLISTING")]
[DataMemberAttribute]
public:
property long long KitProductMasterId {
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

