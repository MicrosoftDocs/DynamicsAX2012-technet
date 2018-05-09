---
title: SecurityManager.ChangePassword Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: ChangePassword Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ChangePassword(System.String,System.String,System.String,System.String,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.securitymanager.changepassword(v=AX.60)
ms:contentKeyID: 65322462
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.SecurityManager.ChangePassword
dev_langs:
- CSharp
- C++
- VB
---

# ChangePassword Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub ChangePassword ( _
    authenticationProvider As String, _
    staffId As String, _
    oldPassword As String, _
    newPassword As String, _
    changePassword As Boolean, _
    transactionId As String _
)
'Usage
Dim instance As SecurityManager
Dim authenticationProvider As String
Dim staffId As String
Dim oldPassword As String
Dim newPassword As String
Dim changePassword As Boolean
Dim transactionId As String

instance.ChangePassword(authenticationProvider, _
    staffId, oldPassword, newPassword, _
    changePassword, transactionId)
```

``` csharp
public void ChangePassword(
    string authenticationProvider,
    string staffId,
    string oldPassword,
    string newPassword,
    bool changePassword,
    string transactionId
)
```

``` c++
public:
void ChangePassword(
    String^ authenticationProvider, 
    String^ staffId, 
    String^ oldPassword, 
    String^ newPassword, 
    bool changePassword, 
    String^ transactionId
)
```

#### Parameters

  - authenticationProvider  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - oldPassword  
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

