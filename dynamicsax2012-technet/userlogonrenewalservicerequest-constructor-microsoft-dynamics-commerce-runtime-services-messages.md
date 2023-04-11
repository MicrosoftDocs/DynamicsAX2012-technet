---
title: UserLogOnRenewalServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserLogOnRenewalServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnRenewalServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Device,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonrenewalservicerequest.userlogonrenewalservicerequest(v=AX.60)
ms:contentKeyID: 65320910
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnRenewalServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UserLogOnRenewalServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    device As Device, _
    staffId As String _
)
'Usage
Dim device As Device
Dim staffId As String

Dim instance As New UserLogOnRenewalServiceRequest(device, _
    staffId)
```

``` csharp
public UserLogOnRenewalServiceRequest(
    Device device,
    string staffId
)
```

``` c++
public:
UserLogOnRenewalServiceRequest(
    Device^ device, 
    String^ staffId
)
```

#### Parameters

  - device  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UserLogOnRenewalServiceRequest Class](userlogonrenewalservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

