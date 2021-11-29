---
title: Cart.AvailableDepositAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AvailableDepositAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.AvailableDepositAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.availabledepositamount(v=AX.60)
ms:contentKeyID: 65318284
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.AvailableDepositAmount
dev_langs:
- CSharp
- C++
- VB
---

# AvailableDepositAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AVAILABLEDEPOSITAMOUNT")> _
<ReadOnlyAttribute("AVAILABLEDEPOSITAMOUNT")> _
Public Property AvailableDepositAmount As Decimal
    Get
    Set
'Usage
Dim instance As Cart
Dim value As Decimal

value = instance.AvailableDepositAmount

instance.AvailableDepositAmount = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AVAILABLEDEPOSITAMOUNT")]
[ReadOnlyAttribute("AVAILABLEDEPOSITAMOUNT")]
public decimal AvailableDepositAmount { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AVAILABLEDEPOSITAMOUNT")]
[ReadOnlyAttribute(L"AVAILABLEDEPOSITAMOUNT")]
public:
property Decimal AvailableDepositAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

