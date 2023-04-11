---
title: TransactionServiceClient.RegisterPunchInOut Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: RegisterPunchInOut Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RegisterPunchInOut(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.registerpunchinout(v=AX.60)
ms:contentKeyID: 62211142
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RegisterPunchInOut
dev_langs:
- CSharp
- C++
- VB
---

# RegisterPunchInOut Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Call this method to register clock in/ out for the employee.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function RegisterPunchInOut ( _
    staffId As String, _
    terminalId As String, _
    methodName As String _
) As Nullable(Of DateTimeOffset)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim terminalId As String
Dim methodName As String
Dim returnValue As Nullable(Of DateTimeOffset)

returnValue = instance.RegisterPunchInOut(staffId, _
    terminalId, methodName)
```

``` csharp
public Nullable<DateTimeOffset> RegisterPunchInOut(
    string staffId,
    string terminalId,
    string methodName
)
```

``` c++
public:
Nullable<DateTimeOffset> RegisterPunchInOut(
    String^ staffId, 
    String^ terminalId, 
    String^ methodName
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - methodName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns the current clock in / clock out date time offset.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

