---
title: TransactionServiceClient.StaffLogOff Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: StaffLogOff Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffLogOff(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.stafflogoff(v=AX.60)
ms:contentKeyID: 49819621
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffLogOff
dev_langs:
- CSharp
- C++
- VB
---

# StaffLogOff Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Logs the specified user off.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub StaffLogOff ( _
    staffId As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim storeId As String
Dim terminalId As String

instance.StaffLogOff(staffId, storeId, _
    terminalId)
```

``` csharp
public void StaffLogOff(
    string staffId,
    string storeId,
    string terminalId
)
```

``` c++
public:
void StaffLogOff(
    String^ staffId, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

