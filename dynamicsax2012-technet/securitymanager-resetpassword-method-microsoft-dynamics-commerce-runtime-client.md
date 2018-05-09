---
title: SecurityManager.ResetPassword Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ResetPassword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ResetPassword(System.String,System.String,System.String,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.securitymanager.resetpassword(v=AX.60)
ms:contentKeyID: 65319528
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ResetPassword
dev_langs:
- CSharp
- C++
- VB
---

# ResetPassword Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub ResetPassword ( _
    authenticationProvider As String, _
    targetUserId As String, _
    newPassword As String, _
    changePassword As Boolean, _
    transactionId As String _
)
'Usage
Dim instance As SecurityManager
Dim authenticationProvider As String
Dim targetUserId As String
Dim newPassword As String
Dim changePassword As Boolean
Dim transactionId As String

instance.ResetPassword(authenticationProvider, _
    targetUserId, newPassword, changePassword, _
    transactionId)
```

``` csharp
public void ResetPassword(
    string authenticationProvider,
    string targetUserId,
    string newPassword,
    bool changePassword,
    string transactionId
)
```

``` c++
public:
void ResetPassword(
    String^ authenticationProvider, 
    String^ targetUserId, 
    String^ newPassword, 
    bool changePassword, 
    String^ transactionId
)
```

#### Parameters

  - authenticationProvider  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - targetUserId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - newPassword  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - changePassword  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[SecurityManager Class](securitymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

