---
title: OfflineTransactionManager.SaveOfflineTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: SaveOfflineTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.SaveOfflineTransactions(System.Byte[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.offlinetransactionmanager.saveofflinetransactions(v=AX.60)
ms:contentKeyID: 65319522
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.SaveOfflineTransactions
dev_langs:
- CSharp
- C++
- VB
---

# SaveOfflineTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub SaveOfflineTransactions ( _
    compressedTransactions As Byte() _
)
'Usage
Dim instance As OfflineTransactionManager
Dim compressedTransactions As Byte()

instance.SaveOfflineTransactions(compressedTransactions)
```

``` csharp
public void SaveOfflineTransactions(
    byte[] compressedTransactions
)
```

``` c++
public:
void SaveOfflineTransactions(
    array<unsigned char>^ compressedTransactions
)
```

#### Parameters

  - compressedTransactions  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[OfflineTransactionManager Class](offlinetransactionmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

