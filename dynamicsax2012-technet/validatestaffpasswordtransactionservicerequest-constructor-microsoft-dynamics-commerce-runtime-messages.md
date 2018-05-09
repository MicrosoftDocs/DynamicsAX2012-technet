---
title: ValidateStaffPasswordTransactionServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ValidateStaffPasswordTransactionServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateStaffPasswordTransactionServiceRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.validatestaffpasswordtransactionservicerequest.validatestaffpasswordtransactionservicerequest(v=AX.60)
ms:contentKeyID: 65320131
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ValidateStaffPasswordTransactionServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ValidateStaffPasswordTransactionServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    staffId As String, _
    password As String _
)
'Usage
Dim staffId As String
Dim password As String

Dim instance As New ValidateStaffPasswordTransactionServiceRequest(staffId, _
    password)
```

``` csharp
public ValidateStaffPasswordTransactionServiceRequest(
    string staffId,
    string password
)
```

``` c++
public:
ValidateStaffPasswordTransactionServiceRequest(
    String^ staffId, 
    String^ password
)
```

#### Parameters

  - staffId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - password  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ValidateStaffPasswordTransactionServiceRequest Class](validatestaffpasswordtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

