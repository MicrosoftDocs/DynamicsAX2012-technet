---
title: OfflineTransactionManager.GetOfflineTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOfflineTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.GetOfflineTransactions(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.offlinetransactionmanager.getofflinetransactions(v=AX.60)
ms:contentKeyID: 65318217
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.GetOfflineTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetOfflineTransactions Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOfflineTransactions ( _
    transactionIds As IEnumerable(Of String) _
) As Byte()
'Usage
Dim instance As OfflineTransactionManager
Dim transactionIds As IEnumerable(Of String)
Dim returnValue As Byte()

returnValue = instance.GetOfflineTransactions(transactionIds)
```

``` csharp
public byte[] GetOfflineTransactions(
    IEnumerable<string> transactionIds
)
```

``` c++
public:
array<unsigned char>^ GetOfflineTransactions(
    IEnumerable<String^>^ transactionIds
)
```

#### Parameters

  - transactionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[OfflineTransactionManager Class](offlinetransactionmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

