---
title: CustomerDataManager.SaveCustomerAccountActivationRequest Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SaveCustomerAccountActivationRequest Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.SaveCustomerAccountActivationRequest(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.customerdatamanager.savecustomeraccountactivationrequest(v=AX.60)
ms:contentKeyID: 62211283
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CustomerDataManager.SaveCustomerAccountActivationRequest
dev_langs:
- CSharp
- C++
- VB
---

# SaveCustomerAccountActivationRequest Method

Save customer account activation request to channel DB.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub SaveCustomerAccountActivationRequest ( _
    email As String, _
    activationToken As String _
)
'Usage
Dim instance As CustomerDataManager
Dim email As String
Dim activationToken As String

instance.SaveCustomerAccountActivationRequest(email, _
    activationToken)
```

``` csharp
public void SaveCustomerAccountActivationRequest(
    string email,
    string activationToken
)
```

``` c++
public:
void SaveCustomerAccountActivationRequest(
    String^ email, 
    String^ activationToken
)
```

#### Parameters

  - email  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerDataManager Class](customerdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

