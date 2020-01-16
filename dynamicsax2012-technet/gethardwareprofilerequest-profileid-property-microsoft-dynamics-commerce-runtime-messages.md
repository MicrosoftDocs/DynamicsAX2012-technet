---
title: GetHardwareProfileRequest.ProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetHardwareProfileRequest.ProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gethardwareprofilerequest.profileid(v=AX.60)
ms:contentKeyID: 62212849
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetHardwareProfileRequest.ProfileId
dev_langs:
- CSharp
- C++
- VB
---

# ProfileId Property

Gets or sets the profile identification.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProfileId As String
    Get
    Set
'Usage
Dim instance As GetHardwareProfileRequest
Dim value As String

value = instance.ProfileId

instance.ProfileId = value
```

``` csharp
[DataMemberAttribute]
public string ProfileId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ProfileId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetHardwareProfileRequest Class](gethardwareprofilerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

