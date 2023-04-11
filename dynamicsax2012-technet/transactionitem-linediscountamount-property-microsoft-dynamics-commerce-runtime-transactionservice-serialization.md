---
title: TransactionItem.LineDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: LineDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.LineDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.linediscountamount(v=AX.60)
ms:contentKeyID: 49845765
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.LineDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# LineDiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the line discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property LineDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Decimal

value = instance.LineDiscountAmount

instance.LineDiscountAmount = value
```

``` csharp
public decimal LineDiscountAmount { get; set; }
```

``` c++
public:
property Decimal LineDiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The line discount amount.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

