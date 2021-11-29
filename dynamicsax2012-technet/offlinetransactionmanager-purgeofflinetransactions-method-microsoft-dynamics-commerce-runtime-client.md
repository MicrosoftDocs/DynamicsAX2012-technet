---
title: OfflineTransactionManager.PurgeOfflineTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: PurgeOfflineTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.PurgeOfflineTransactions(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.offlinetransactionmanager.purgeofflinetransactions(v=AX.60)
ms:contentKeyID: 65319188
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.PurgeOfflineTransactions
dev_langs:
- CSharp
- C++
- VB
---

# PurgeOfflineTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub PurgeOfflineTransactions ( _
    transactionIds As IEnumerable(Of String) _
)
'Usage
Dim instance As OfflineTransactionManager
Dim transactionIds As IEnumerable(Of String)

instance.PurgeOfflineTransactions(transactionIds)
```

``` csharp
public void PurgeOfflineTransactions(
    IEnumerable<string> transactionIds
)
```

``` c++
public:
void PurgeOfflineTransactions(
    IEnumerable<String^>^ transactionIds
)
```

#### Parameters

  - transactionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[OfflineTransactionManager Class](offlinetransactionmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

