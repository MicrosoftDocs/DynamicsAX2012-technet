---
title: ChannelProfile.ProfileTypeIdentifier Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProfileTypeIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile.ProfileTypeIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelprofile.profiletypeidentifier(v=AX.60)
ms:contentKeyID: 62208208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile.ProfileTypeIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# ProfileTypeIdentifier Property

Gets the profile type identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHANNELPROFILETYPE")> _
<DataMemberAttribute> _
Public Property ProfileTypeIdentifier As Integer
    Get
    Friend Set
'Usage
Dim instance As ChannelProfile
Dim value As Integer

value = instance.ProfileTypeIdentifier
```

``` csharp
[ColumnAttribute("CHANNELPROFILETYPE")]
[DataMemberAttribute]
public int ProfileTypeIdentifier { get; internal set; }
```

``` c++
[ColumnAttribute(L"CHANNELPROFILETYPE")]
[DataMemberAttribute]
public:
property int ProfileTypeIdentifier {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChannelProfile Class](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

