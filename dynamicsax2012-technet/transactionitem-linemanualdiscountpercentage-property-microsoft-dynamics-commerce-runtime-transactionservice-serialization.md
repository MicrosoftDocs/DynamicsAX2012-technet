---
title: TransactionItem.LineManualDiscountPercentage Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: LineManualDiscountPercentage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.LineManualDiscountPercentage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.linemanualdiscountpercentage(v=AX.60)
ms:contentKeyID: 62213620
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.LineManualDiscountPercentage
dev_langs:
- CSharp
- C++
- VB
---

# LineManualDiscountPercentage Property

Gets or sets the line manual discount percentage.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property LineManualDiscountPercentage As Decimal
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Decimal

value = instance.LineManualDiscountPercentage

instance.LineManualDiscountPercentage = value
```

``` csharp
public decimal LineManualDiscountPercentage { get; set; }
```

``` c++
public:
property Decimal LineManualDiscountPercentage {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

