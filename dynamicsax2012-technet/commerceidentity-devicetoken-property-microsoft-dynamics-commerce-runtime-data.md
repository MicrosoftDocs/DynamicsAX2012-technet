---
title: CommerceIdentity.DeviceToken Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeviceToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.DeviceToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.devicetoken(v=AX.60)
ms:contentKeyID: 62208527
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.DeviceToken
dev_langs:
- CSharp
- C++
- VB
---

# DeviceToken Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceToken As String
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String

value = instance.DeviceToken

instance.DeviceToken = value
```

``` csharp
[DataMemberAttribute]
public string DeviceToken { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceToken {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

