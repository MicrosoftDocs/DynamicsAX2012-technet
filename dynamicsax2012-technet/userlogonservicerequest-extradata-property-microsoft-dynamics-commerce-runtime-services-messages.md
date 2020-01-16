---
title: UserLogOnServiceRequest.ExtraData Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ExtraData Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.ExtraData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.userlogonservicerequest.extradata(v=AX.60)
ms:contentKeyID: 62210257
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.UserLogOnServiceRequest.ExtraData
dev_langs:
- CSharp
- C++
- VB
---

# ExtraData Property

Gets the Extra Data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExtraData As String
    Get
    Private Set
'Usage
Dim instance As UserLogOnServiceRequest
Dim value As String

value = instance.ExtraData
```

``` csharp
[DataMemberAttribute]
public string ExtraData { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ExtraData {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[UserLogOnServiceRequest Class](userlogonservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

