---
title: TransactionItem.PeriodicDiscountAmount Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: PeriodicDiscountAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.PeriodicDiscountAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.periodicdiscountamount(v=AX.60)
ms:contentKeyID: 49822968
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.PeriodicDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the periodic discount amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PeriodicDiscountAmount As Decimal
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Decimal

value = instance.PeriodicDiscountAmount

instance.PeriodicDiscountAmount = value
```

``` csharp
public decimal PeriodicDiscountAmount { get; set; }
```

``` c++
public:
property Decimal PeriodicDiscountAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The periodic discount amount.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

