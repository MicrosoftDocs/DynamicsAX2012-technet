---
title: TransactionServiceClient.RegisterStartBreak Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: RegisterStartBreak Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RegisterStartBreak(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.registerstartbreak(v=AX.60)
ms:contentKeyID: 62212537
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RegisterStartBreak
dev_langs:
- CSharp
- C++
- VB
---

# RegisterStartBreak Method

Register for break time (breakfromwork / breakforlunch).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function RegisterStartBreak ( _
    staffId As String, _
    terminalId As String, _
    jobId As String _
) As Nullable(Of DateTimeOffset)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim terminalId As String
Dim jobId As String
Dim returnValue As Nullable(Of DateTimeOffset)

returnValue = instance.RegisterStartBreak(staffId, _
    terminalId, jobId)
```

``` csharp
public Nullable<DateTimeOffset> RegisterStartBreak(
    string staffId,
    string terminalId,
    string jobId
)
```

``` c++
public:
Nullable<DateTimeOffset> RegisterStartBreak(
    String^ staffId, 
    String^ terminalId, 
    String^ jobId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - jobId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))\>  
Returns the current break out date time offset.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

