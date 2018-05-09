---
title: UserLogOnServiceRequest.LogOnType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LogOnType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.LogOnType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.logontype(v=AX.60)
ms:contentKeyID: 62215175
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.LogOnType
dev_langs:
- CSharp
- C++
- VB
---

# LogOnType Property

Gets the Logon Type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnType As LogOnType
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceRequest
Dim value As LogOnType

value = instance.LogOnType
```

``` csharp
[DataMemberAttribute]
public LogOnType LogOnType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property LogOnType LogOnType {
    LogOnType get ();
    private: void set (LogOnType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LogOnType](logontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

