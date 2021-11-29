---
title: UserAuthenticationRequest.LogOnType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: LogOnType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.LogOnType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.userauthenticationrequest.logontype(v=AX.60)
ms:contentKeyID: 62213873
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UserAuthenticationRequest.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Logon Type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnType As LogOnType
    Get
    Set
'Usage
Dim instance As UserAuthenticationRequest
Dim value As LogOnType

value = instance.LogOnType

instance.LogOnType = value
```

``` csharp
[DataMemberAttribute]
public LogOnType LogOnType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnType LogOnType {
    LogOnType get ();
    void set (LogOnType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Extra Data.  

## See Also

#### Reference

[UserAuthenticationRequest Class](userauthenticationrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

