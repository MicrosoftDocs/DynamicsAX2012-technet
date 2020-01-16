---
title: TransactionServiceClient.StaffLogOn Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: StaffLogOn Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffLogOn(System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.stafflogon(v=AX.60)
ms:contentKeyID: 49842667
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffLogOn
dev_langs:
- CSharp
- C++
- VB
---

# StaffLogOn Method

Logs the specified user on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub StaffLogOn ( _
    staffId As String, _
    storeId As String, _
    terminalId As String, _
    password As String _
)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim storeId As String
Dim terminalId As String
Dim password As String

instance.StaffLogOn(staffId, storeId, _
    terminalId, password)
```

``` csharp
public void StaffLogOn(
    string staffId,
    string storeId,
    string terminalId,
    string password
)
```

``` c++
public:
void StaffLogOn(
    String^ staffId, 
    String^ storeId, 
    String^ terminalId, 
    String^ password
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

<!-- end list -->

  - password  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

