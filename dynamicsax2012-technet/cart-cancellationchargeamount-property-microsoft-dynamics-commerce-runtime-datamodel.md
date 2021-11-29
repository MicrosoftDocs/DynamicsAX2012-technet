---
title: Cart.CancellationChargeAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CancellationChargeAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CancellationChargeAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.cancellationchargeamount(v=AX.60)
ms:contentKeyID: 62206884
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.CancellationChargeAmount
dev_langs:
- CSharp
- C++
- VB
---

# CancellationChargeAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the charge amount related to order cancellation (customer order).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CANCELLATIONCHARGE")> _
<DataMemberAttribute> _
Public Property CancellationChargeAmount As Nullable(Of Decimal)
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Nullable(Of Decimal)

value = instance.CancellationChargeAmount

instance.CancellationChargeAmount = value
```

``` csharp
[ColumnAttribute("CANCELLATIONCHARGE")]
[DataMemberAttribute]
public Nullable<decimal> CancellationChargeAmount { get; set; }
```

``` c++
[ColumnAttribute(L"CANCELLATIONCHARGE")]
[DataMemberAttribute]
public:
property Nullable<Decimal> CancellationChargeAmount {
    Nullable<Decimal> get ();
    void set (Nullable<Decimal> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

