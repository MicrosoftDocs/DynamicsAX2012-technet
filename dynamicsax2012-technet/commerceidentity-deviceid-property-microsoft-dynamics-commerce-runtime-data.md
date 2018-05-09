---
title: CommerceIdentity.DeviceId Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeviceId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.DeviceId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.deviceid(v=AX.60)
ms:contentKeyID: 62210864
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.DeviceId
dev_langs:
- CSharp
- C++
- VB
---

# DeviceId Property

Gets the terminal identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DeviceId As String
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String

value = instance.DeviceId

instance.DeviceId = value
```

``` csharp
[DataMemberAttribute]
public string DeviceId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ DeviceId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

