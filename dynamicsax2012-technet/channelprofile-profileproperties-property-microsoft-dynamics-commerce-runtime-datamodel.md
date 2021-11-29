---
title: ChannelProfile.ProfileProperties Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProfileProperties Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile.ProfileProperties
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelprofile.profileproperties(v=AX.60)
ms:contentKeyID: 49837887
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile.ProfileProperties
dev_langs:
- CSharp
- C++
- VB
---

# ProfileProperties Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of channel profile properties.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProfileProperties As ReadOnlyCollection(Of ChannelProfileProperty)
    Get
    Private Set
'Usage
Dim instance As ChannelProfile
Dim value As ReadOnlyCollection(Of ChannelProfileProperty)

value = instance.ProfileProperties
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ChannelProfileProperty> ProfileProperties { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ChannelProfileProperty^>^ ProfileProperties {
    ReadOnlyCollection<ChannelProfileProperty^>^ get ();
    private: void set (ReadOnlyCollection<ChannelProfileProperty^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelProfileProperty](channelprofileproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[ChannelProfile Class](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

