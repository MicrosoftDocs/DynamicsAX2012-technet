---
title: CustomerDataManager.ValidateAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ValidateAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.ValidateAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.validateaccountactivationrequest(v=AX.60)
ms:contentKeyID: 62209626
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.ValidateAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# ValidateAccountActivationRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Validate the account activation request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function ValidateAccountActivationRequest ( _
    email As String, _
    activationToken As String _
) As Boolean
'Usage
Dim instance As CustomerDataManager
Dim email As String
Dim activationToken As String
Dim returnValue As Boolean

returnValue = instance.ValidateAccountActivationRequest(email, _
    activationToken)
```

``` csharp
public bool ValidateAccountActivationRequest(
    string email,
    string activationToken
)
```

``` c++
public:
bool ValidateAccountActivationRequest(
    String^ email, 
    String^ activationToken
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if the request is valid; otherwise return false.  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

