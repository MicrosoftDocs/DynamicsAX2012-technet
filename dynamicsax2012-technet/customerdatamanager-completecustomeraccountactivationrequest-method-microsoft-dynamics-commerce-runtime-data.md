---
title: CustomerDataManager.CompleteCustomerAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CompleteCustomerAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.CompleteCustomerAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.completecustomeraccountactivationrequest(v=AX.60)
ms:contentKeyID: 62210620
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.CompleteCustomerAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# CompleteCustomerAccountActivationRequest Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Save customer account activation request to channel DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub CompleteCustomerAccountActivationRequest ( _
    email As String, _
    activationToken As String _
)
'Usage
Dim instance As CustomerDataManager
Dim email As String
Dim activationToken As String

instance.CompleteCustomerAccountActivationRequest(email, _
    activationToken)
```

``` csharp
public void CompleteCustomerAccountActivationRequest(
    string email,
    string activationToken
)
```

``` c++
public:
void CompleteCustomerAccountActivationRequest(
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

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

