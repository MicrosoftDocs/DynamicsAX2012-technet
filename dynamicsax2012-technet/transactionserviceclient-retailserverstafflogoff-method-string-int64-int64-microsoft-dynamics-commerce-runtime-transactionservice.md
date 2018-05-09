---
title: TransactionServiceClient.RetailServerStaffLogOff Method (String, Int64, Int64) (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: RetailServerStaffLogOff Method (String, Int64, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RetailServerStaffLogOff(System.String,System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.retailserverstafflogoff(v=AX.60)
ms:contentKeyID: 62206927
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RetailServerStaffLogOff Method (String, Int64, Int64)

Logs the specified user off.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub RetailServerStaffLogOff ( _
    staffId As String, _
    storeRecordId As Long, _
    terminalRecordId As Long _
)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim storeRecordId As Long
Dim terminalRecordId As Long

instance.RetailServerStaffLogOff(staffId, _
    storeRecordId, terminalRecordId)
```

``` csharp
public void RetailServerStaffLogOff(
    string staffId,
    long storeRecordId,
    long terminalRecordId
)
```

``` c++
public:
void RetailServerStaffLogOff(
    String^ staffId, 
    long long storeRecordId, 
    long long terminalRecordId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[RetailServerStaffLogOff Overload](transactionserviceclient-retailserverstafflogoff-method-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

