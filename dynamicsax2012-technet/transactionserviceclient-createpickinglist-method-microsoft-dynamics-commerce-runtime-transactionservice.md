---
title: TransactionServiceClient.CreatePickingList Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: CreatePickingList Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreatePickingList(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.createpickinglist(v=AX.60)
ms:contentKeyID: 62207399
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.CreatePickingList
dev_langs:
- CSharp
- C++
- VB
---

# CreatePickingList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates picking list.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub CreatePickingList ( _
    salesId As String, _
    inventoryLocationId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim salesId As String
Dim inventoryLocationId As String

instance.CreatePickingList(salesId, inventoryLocationId)
```

``` csharp
public void CreatePickingList(
    string salesId,
    string inventoryLocationId
)
```

``` c++
public:
void CreatePickingList(
    String^ salesId, 
    String^ inventoryLocationId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventoryLocationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

