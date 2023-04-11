---
title: CustomerManager.FinalizeAccountActivation Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: FinalizeAccountActivation Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.FinalizeAccountActivation(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.customermanager.finalizeaccountactivation(v=AX.60)
ms:contentKeyID: 62211668
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.CustomerManager.FinalizeAccountActivation
dev_langs:
- CSharp
- C++
- VB
---

# FinalizeAccountActivation Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Finalize the customer account activation request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Sub FinalizeAccountActivation ( _
    emailAddress As String, _
    activationToken As String _
)
'Usage
Dim instance As CustomerManager
Dim emailAddress As String
Dim activationToken As String

instance.FinalizeAccountActivation(emailAddress, _
    activationToken)
```

``` csharp
public void FinalizeAccountActivation(
    string emailAddress,
    string activationToken
)
```

``` c++
public:
void FinalizeAccountActivation(
    String^ emailAddress, 
    String^ activationToken
)
```

#### Parameters

  - emailAddress  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - activationToken  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CustomerManager Class](customermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

