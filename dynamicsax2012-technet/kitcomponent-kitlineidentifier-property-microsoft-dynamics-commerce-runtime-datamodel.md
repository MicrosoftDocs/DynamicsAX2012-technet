---
title: KitComponent.KitLineIdentifier Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: KitLineIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.KitLineIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.kitcomponent.kitlineidentifier(v=AX.60)
ms:contentKeyID: 62214504
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.KitComponent.KitLineIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# KitLineIdentifier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the kit line identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("KITLINEIDENTIFIER")> _
Public Property KitLineIdentifier As Long
    Get
    Friend Set
'Usage
Dim instance As KitComponent
Dim value As Long

value = instance.KitLineIdentifier
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("KITLINEIDENTIFIER")]
public long KitLineIdentifier { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"KITLINEIDENTIFIER")]
public:
property long long KitLineIdentifier {
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

