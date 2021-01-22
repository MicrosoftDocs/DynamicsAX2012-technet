---
title: CommercePrincipal.DeviceId Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeviceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.DeviceId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.deviceid(v=AX.60)
ms:contentKeyID: 62214478
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.DeviceId
dev_langs:
- CSharp
- C++
- VB
---

# DeviceId Property

Gets the device identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public ReadOnly Property DeviceId As String
    Get
'Usage
Dim instance As CommercePrincipal
Dim value As String

value = instance.DeviceId
```

``` csharp
[DataMemberAttribute]
public string DeviceId { get; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceId {
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

