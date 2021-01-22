---
title: Cart.PrepaymentAppliedOnPickup Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PrepaymentAppliedOnPickup Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.PrepaymentAppliedOnPickup
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.prepaymentappliedonpickup(v=AX.60)
ms:contentKeyID: 62202396
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.PrepaymentAppliedOnPickup
dev_langs:
- CSharp
- C++
- VB
---

# PrepaymentAppliedOnPickup Property

Gets or sets the amount of the prepayment that is applied on the pickup operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("PREPAYMENTAPPLIEDONPICKUP")> _
<ColumnAttribute("PREPAYMENTAPPLIEDONPICKUP")> _
<DataMemberAttribute> _
Public Property PrepaymentAppliedOnPickup As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.PrepaymentAppliedOnPickup

instance.PrepaymentAppliedOnPickup = value
```

``` csharp
[ReadOnlyAttribute("PREPAYMENTAPPLIEDONPICKUP")]
[ColumnAttribute("PREPAYMENTAPPLIEDONPICKUP")]
[DataMemberAttribute]
public decimal PrepaymentAppliedOnPickup { get; set; }
```

``` c++
[ReadOnlyAttribute(L"PREPAYMENTAPPLIEDONPICKUP")]
[ColumnAttribute(L"PREPAYMENTAPPLIEDONPICKUP")]
[DataMemberAttribute]
public:
property Decimal PrepaymentAppliedOnPickup {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

