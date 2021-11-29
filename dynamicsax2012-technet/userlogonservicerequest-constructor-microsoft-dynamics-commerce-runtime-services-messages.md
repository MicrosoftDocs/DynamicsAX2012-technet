---
title: UserLogOnServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: UserLogOnServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Device,Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType,Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.userlogonservicerequest(v=AX.60)
ms:contentKeyID: 65321235
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UserLogOnServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    device As Device, _
    logOnType As LogOnType, _
    retailOperation As RetailOperation, _
    staffId As String, _
    password As String, _
    logOnKey As String, _
    extraData As String _
)
'Usage
Dim device As Device
Dim logOnType As LogOnType
Dim retailOperation As RetailOperation
Dim staffId As String
Dim password As String
Dim logOnKey As String
Dim extraData As String

Dim instance As New UserLogOnServiceRequest(device, _
    logOnType, retailOperation, staffId, _
    password, logOnKey, extraData)
```

``` csharp
public UserLogOnServiceRequest(
    Device device,
    LogOnType logOnType,
    RetailOperation retailOperation,
    string staffId,
    string password,
    string logOnKey,
    string extraData
)
```

``` c++
public:
UserLogOnServiceRequest(
    Device^ device, 
    LogOnType logOnType, 
    RetailOperation retailOperation, 
    String^ staffId, 
    String^ password, 
    String^ logOnKey, 
    String^ extraData
)
```

#### Parameters

  - device  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Device](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - logOnType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - retailOperation  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailOperation](retailoperation-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - staffId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - password  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - logOnKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - extraData  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

