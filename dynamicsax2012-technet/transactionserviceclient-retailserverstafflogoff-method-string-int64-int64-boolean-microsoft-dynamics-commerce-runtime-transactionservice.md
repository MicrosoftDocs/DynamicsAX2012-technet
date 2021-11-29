---
title: TransactionServiceClient.RetailServerStaffLogOff Method (String, Int64, Int64, Boolean) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: RetailServerStaffLogOff Method (String, Int64, Int64, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RetailServerStaffLogOff(System.String,System.Int64,System.Int64,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.retailserverstafflogoff(v=AX.60)
ms:contentKeyID: 62213195
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RetailServerStaffLogOff Method (String, Int64, Int64, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Logs the specified user off.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub RetailServerStaffLogOff ( _
    staffId As String, _
    storeRecordId As Long, _
    terminalRecordId As Long, _
    logOffFromStore As Boolean _
)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim storeRecordId As Long
Dim terminalRecordId As Long
Dim logOffFromStore As Boolean

instance.RetailServerStaffLogOff(staffId, _
    storeRecordId, terminalRecordId, _
    logOffFromStore)
```

``` csharp
public void RetailServerStaffLogOff(
    string staffId,
    long storeRecordId,
    long terminalRecordId,
    bool logOffFromStore
)
```

``` c++
public:
void RetailServerStaffLogOff(
    String^ staffId, 
    long long storeRecordId, 
    long long terminalRecordId, 
    bool logOffFromStore
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - logOffFromStore  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[RetailServerStaffLogOff Overload](transactionserviceclient-retailserverstafflogoff-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

