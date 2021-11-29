---
title: Cart.BeginDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BeginDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.BeginDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.begindatetime(v=AX.60)
ms:contentKeyID: 65318650
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.BeginDateTime
dev_langs:
- CSharp
- C++
- VB
---

# BeginDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BEGINDATETIME")> _
Public Property BeginDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of DateTimeOffset)

value = instance.BeginDateTime

instance.BeginDateTime = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BEGINDATETIME")]
public Nullable<DateTimeOffset> BeginDateTime { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BEGINDATETIME")]
public:
property Nullable<DateTimeOffset> BeginDateTime {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

