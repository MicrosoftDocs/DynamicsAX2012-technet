---
title: Cart.ModifiedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ModifiedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ModifiedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.modifieddatetime(v=AX.60)
ms:contentKeyID: 62212613
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.ModifiedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# ModifiedDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the last modified date of the sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("MODIFIEDDATETIME")> _
Public Property ModifiedDateTime As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of DateTimeOffset)

value = instance.ModifiedDateTime

instance.ModifiedDateTime = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("MODIFIEDDATETIME")]
public Nullable<DateTimeOffset> ModifiedDateTime { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"MODIFIEDDATETIME")]
public:
property Nullable<DateTimeOffset> ModifiedDateTime {
    Nullable<DateTimeOffset> get ();
    void set (Nullable<DateTimeOffset> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

