---
title: Cart.BusinessDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BusinessDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.BusinessDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.businessdate(v=AX.60)
ms:contentKeyID: 65319103
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.BusinessDate
dev_langs:
- CSharp
- C++
- VB
---

# BusinessDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("BUSINESSDATE")> _
<ColumnAttribute("BUSINESSDATE")> _
<DataMemberAttribute> _
Public Property BusinessDate As Nullable(Of DateTimeOffset)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of DateTimeOffset)

value = instance.BusinessDate

instance.BusinessDate = value
```

``` csharp
[ReadOnlyAttribute("BUSINESSDATE")]
[ColumnAttribute("BUSINESSDATE")]
[DataMemberAttribute]
public Nullable<DateTimeOffset> BusinessDate { get; set; }
```

``` c++
[ReadOnlyAttribute(L"BUSINESSDATE")]
[ColumnAttribute(L"BUSINESSDATE")]
[DataMemberAttribute]
public:
property Nullable<DateTimeOffset> BusinessDate {
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

