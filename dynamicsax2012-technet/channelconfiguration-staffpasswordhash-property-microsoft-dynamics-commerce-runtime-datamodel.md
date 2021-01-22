---
title: ChannelConfiguration.StaffPasswordHash Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffPasswordHash Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.StaffPasswordHash
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.staffpasswordhash(v=AX.60)
ms:contentKeyID: 62208136
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.StaffPasswordHash
dev_langs:
- CSharp
- C++
- VB
---

# StaffPasswordHash Property

Gets the staff password hash type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property StaffPasswordHash As String
    Get
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.StaffPasswordHash
```

``` csharp
[IgnoreDataMemberAttribute]
public string StaffPasswordHash { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ StaffPasswordHash {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

