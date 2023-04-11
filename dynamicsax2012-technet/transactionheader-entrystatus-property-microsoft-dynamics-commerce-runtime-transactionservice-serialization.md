---
title: TransactionHeader.EntryStatus Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization)
TOCTitle: EntryStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.EntryStatus
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.serialization.transactionheader.entrystatus(v=AX.60)
ms:contentKeyID: 49856270
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization.TransactionHeader.EntryStatus
dev_langs:
- CSharp
- C++
- VB
---

# EntryStatus Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the entry status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property EntryStatus As String
    Get
    Set
'Usage
Dim instance As TransactionHeader
Dim value As String

value = instance.EntryStatus

instance.EntryStatus = value
```

``` csharp
public string EntryStatus { get; set; }
```

``` c++
public:
property String^ EntryStatus {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The entry status.  

## See Also

#### Reference

[TransactionHeader Class](transactionheader-class-microsoft-dynamics-commerce-runtime-transactionservice-serialization.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService.Serialization Namespace](microsoft-dynamics-commerce-runtime-transactionservice-serialization-namespace.md)

