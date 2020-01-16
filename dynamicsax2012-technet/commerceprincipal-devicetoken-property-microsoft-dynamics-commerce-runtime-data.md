---
title: CommercePrincipal.DeviceToken Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeviceToken Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.DeviceToken
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.devicetoken(v=AX.60)
ms:contentKeyID: 62203939
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.DeviceToken
dev_langs:
- CSharp
- C++
- VB
---

# DeviceToken Property

Gets the device token.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property DeviceToken As String
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As String

value = instance.DeviceToken
```

``` csharp
[DataMemberAttribute]
public string DeviceToken { get; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceToken {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

