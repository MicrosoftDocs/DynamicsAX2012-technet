---
title: TransactionHeader.HasLoyaltyPayment Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: HasLoyaltyPayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.HasLoyaltyPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionheader.hasloyaltypayment(v=AX.60)
ms:contentKeyID: 62215058
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.HasLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# HasLoyaltyPayment Property

Gets or sets a value indicating whether the transaction has any posted loyalty tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property HasLoyaltyPayment As Boolean
    Get
    Set
'Usage
Dim instance As TransactionHeader
Dim value As Boolean

value = instance.HasLoyaltyPayment

instance.HasLoyaltyPayment = value
```

``` csharp
public bool HasLoyaltyPayment { get; set; }
```

``` c++
public:
property bool HasLoyaltyPayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value indicating whether the transaction has any posted loyalty tender.  

## See Also

#### Reference

[TransactionHeader Class](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

