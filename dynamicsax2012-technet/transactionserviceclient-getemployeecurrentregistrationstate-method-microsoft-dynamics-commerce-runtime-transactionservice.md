---
title: TransactionServiceClient.GetEmployeeCurrentRegistrationState Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: GetEmployeeCurrentRegistrationState Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetEmployeeCurrentRegistrationState(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.getemployeecurrentregistrationstate(v=AX.60)
ms:contentKeyID: 62209942
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.GetEmployeeCurrentRegistrationState
dev_langs:
- CSharp
- C++
- VB
---

# GetEmployeeCurrentRegistrationState Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets employee current registration state.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Function GetEmployeeCurrentRegistrationState ( _
    staffId As String, _
    terminalId As String _
) As EmployeeActivity
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim terminalId As String
Dim returnValue As EmployeeActivity

returnValue = instance.GetEmployeeCurrentRegistrationState(staffId, _
    terminalId)
```

``` csharp
public EmployeeActivity GetEmployeeCurrentRegistrationState(
    string staffId,
    string terminalId
)
```

``` c++
public:
EmployeeActivity^ GetEmployeeCurrentRegistrationState(
    String^ staffId, 
    String^ terminalId
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.EmployeeActivity](employeeactivity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns the latest activity performed by employee.  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

