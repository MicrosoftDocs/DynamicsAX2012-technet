---
title: TransactionServiceClient.StaffResetPassword Method  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: StaffResetPassword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffResetPassword(System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.transactionserviceclient.staffresetpassword(v=AX.60)
ms:contentKeyID: 62207053
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.TransactionServiceClient.StaffResetPassword
dev_langs:
- CSharp
- C++
- VB
---

# StaffResetPassword Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Reset password for a specified user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Sub StaffResetPassword ( _
    targetUserId As String, _
    newPassword As String, _
    changePassword As Boolean _
)
'Usage
Dim instance As TransactionServiceClient
Dim targetUserId As String
Dim newPassword As String
Dim changePassword As Boolean

instance.StaffResetPassword(targetUserId, _
    newPassword, changePassword)
```

``` csharp
public void StaffResetPassword(
    string targetUserId,
    string newPassword,
    bool changePassword
)
```

``` c++
public:
void StaffResetPassword(
    String^ targetUserId, 
    String^ newPassword, 
    bool changePassword
)
```

#### Parameters

  - targetUserId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newPassword  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - changePassword  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[TransactionServiceClient Class](transactionserviceclient-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

