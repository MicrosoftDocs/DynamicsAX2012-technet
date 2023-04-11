---
title: TransactionItem.ReceiptId Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: ReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.ReceiptId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionitem.receiptid(v=AX.60)
ms:contentKeyID: 49847448
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionItem.ReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the receipt id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property ReceiptId As String
    Get
    Set
'Usage
Dim instance As TransactionItem
Dim value As String

value = instance.ReceiptId

instance.ReceiptId = value
```

``` csharp
public string ReceiptId { get; set; }
```

``` c++
public:
property String^ ReceiptId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The receipt id.  

## See Also

#### Reference

[TransactionItem Class](transactionitem-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

