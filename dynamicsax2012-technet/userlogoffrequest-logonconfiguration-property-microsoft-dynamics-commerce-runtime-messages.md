---
title: UserLogOffRequest.LogOnConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LogOnConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.LogOnConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userlogoffrequest.logonconfiguration(v=AX.60)
ms:contentKeyID: 62210815
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserLogOffRequest.LogOnConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# LogOnConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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
Dim instance As UserLogOffRequest
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

[UserLogOffRequest Class](userlogoffrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

