---
title: UserChangePasswordRequest.LogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest.LogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.userchangepasswordrequest.logonconfiguration(v=AX.60)
ms:contentKeyID: 62210946
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserChangePasswordRequest.LogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# LogOnConfiguration Property

Gets or sets the logon configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnConfiguration As LogOnConfiguration
    Get
    Set
'Usage
Dim instance As UserChangePasswordRequest
Dim value As LogOnConfiguration

value = instance.LogOnConfiguration

instance.LogOnConfiguration = value
```

``` csharp
[DataMemberAttribute]
public LogOnConfiguration LogOnConfiguration { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnConfiguration LogOnConfiguration {
    LogOnConfiguration get ();
    void set (LogOnConfiguration value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnConfiguration](logonconfiguration-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Logon configuration.  

## See Also

#### Reference

[UserChangePasswordRequest Class](userchangepasswordrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

