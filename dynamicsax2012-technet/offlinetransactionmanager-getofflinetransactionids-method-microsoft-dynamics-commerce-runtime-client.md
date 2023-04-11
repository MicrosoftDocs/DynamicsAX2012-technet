---
title: OfflineTransactionManager.GetOfflineTransactionIds Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetOfflineTransactionIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.GetOfflineTransactionIds(System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.offlinetransactionmanager.getofflinetransactionids(v=AX.60)
ms:contentKeyID: 65317670
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OfflineTransactionManager.GetOfflineTransactionIds
dev_langs:
- CSharp
- C++
- VB
---

# GetOfflineTransactionIds Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetOfflineTransactionIds ( _
    numberOfTransactions As Integer _
) As ReadOnlyCollection(Of String)
'Usage
Dim instance As OfflineTransactionManager
Dim numberOfTransactions As Integer
Dim returnValue As ReadOnlyCollection(Of String)

returnValue = instance.GetOfflineTransactionIds(numberOfTransactions)
```

``` csharp
public ReadOnlyCollection<string> GetOfflineTransactionIds(
    int numberOfTransactions
)
```

``` c++
public:
ReadOnlyCollection<String^>^ GetOfflineTransactionIds(
    int numberOfTransactions
)
```

#### Parameters

  - numberOfTransactions  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[OfflineTransactionManager Class](offlinetransactionmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

