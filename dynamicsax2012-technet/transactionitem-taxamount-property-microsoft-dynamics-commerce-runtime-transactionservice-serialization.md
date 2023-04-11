---
title: TransactionItem.TaxAmount Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: TaxAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.TaxAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.taxamount(v=AX.60)
ms:contentKeyID: 49829012
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.TaxAmount
dev_langs:
- CSharp
- C++
- VB
---

# TaxAmount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the tax amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property TaxAmount As Decimal
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Decimal

value = instance.TaxAmount

instance.TaxAmount = value
```

``` csharp
public decimal TaxAmount { get; set; }
```

``` c++
public:
property Decimal TaxAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The tax amount.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

