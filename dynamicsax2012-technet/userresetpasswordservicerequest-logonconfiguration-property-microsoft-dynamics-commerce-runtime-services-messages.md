---
title: UserResetPasswordServiceRequest.LogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.LogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userresetpasswordservicerequest.logonconfiguration(v=AX.60)
ms:contentKeyID: 62209212
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserResetPasswordServiceRequest.LogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# LogOnConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the logon configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnConfiguration As LogOnConfiguration
    Get
    Private Set
'Usage
Dim instance As UserResetPasswordServiceRequest
Dim value As LogOnConfiguration

value = instance.LogOnConfiguration
```

``` csharp
[DataMemberAttribute]
public LogOnConfiguration LogOnConfiguration { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnConfiguration LogOnConfiguration {
    LogOnConfiguration get ();
    private: void set (LogOnConfiguration value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UserResetPasswordServiceRequest Class](userresetpasswordservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

