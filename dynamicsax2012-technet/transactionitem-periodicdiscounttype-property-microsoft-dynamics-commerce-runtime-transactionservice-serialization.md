---
title: TransactionItem.PeriodicDiscountType Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: PeriodicDiscountType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.PeriodicDiscountType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.periodicdiscounttype(v=AX.60)
ms:contentKeyID: 49831974
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.PeriodicDiscountType
dev_langs:
- CSharp
- C++
- VB
---

# PeriodicDiscountType Property

Gets or sets the type of the periodic discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property PeriodicDiscountType As Integer
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As Integer

value = instance.PeriodicDiscountType

instance.PeriodicDiscountType = value
```

``` csharp
public int PeriodicDiscountType { get; set; }
```

``` c++
public:
property int PeriodicDiscountType {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
The type of the periodic discount.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

