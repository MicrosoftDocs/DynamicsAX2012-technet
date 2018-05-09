---
title: TransactionServiceClient.RetailServerStaffLogOnRenewal Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: RetailServerStaffLogOnRenewal Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RetailServerStaffLogOnRenewal(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.retailserverstafflogonrenewal(v=AX.60)
ms:contentKeyID: 62209005
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.RetailServerStaffLogOnRenewal
dev_langs:
- CSharp
- C++
- VB
---

# RetailServerStaffLogOnRenewal Method

Logs the specified user on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function RetailServerStaffLogOnRenewal ( _
    staffId As String _
) As Employee
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim returnValue As Employee

returnValue = instance.RetailServerStaffLogOnRenewal(staffId)
```

``` csharp
public Employee RetailServerStaffLogOnRenewal(
    string staffId
)
```

``` c++
public:
Employee^ RetailServerStaffLogOnRenewal(
    String^ staffId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Employee](employee-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The employee information.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

