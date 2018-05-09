---
title: TransactionServiceClient.StaffChangePassword Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: StaffChangePassword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffChangePassword(System.String,System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.staffchangepassword(v=AX.60)
ms:contentKeyID: 62208120
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffChangePassword
dev_langs:
- CSharp
- C++
- VB
---

# StaffChangePassword Method

Change password for a user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub StaffChangePassword ( _
    staffId As String, _
    oldPasswordHash As String, _
    newPassword As String, _
    changePassword As Boolean _
)
'Usage
Dim instance As TransactionServiceClient
Dim staffId As String
Dim oldPasswordHash As String
Dim newPassword As String
Dim changePassword As Boolean

instance.StaffChangePassword(staffId, _
    oldPasswordHash, newPassword, changePassword)
```

``` csharp
public void StaffChangePassword(
    string staffId,
    string oldPasswordHash,
    string newPassword,
    bool changePassword
)
```

``` c++
public:
void StaffChangePassword(
    String^ staffId, 
    String^ oldPasswordHash, 
    String^ newPassword, 
    bool changePassword
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - oldPasswordHash  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newPassword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - changePassword  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

