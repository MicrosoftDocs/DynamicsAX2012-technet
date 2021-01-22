---
title: ChannelConfiguration.SetProfileProperties Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SetProfileProperties Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.SetProfileProperties(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfileProperty})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.setprofileproperties(v=AX.60)
ms:contentKeyID: 65321139
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.SetProfileProperties
dev_langs:
- CSharp
- C++
- VB
---

# SetProfileProperties Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub SetProfileProperties ( _
    profileProperties As ReadOnlyCollection(Of ChannelProfileProperty) _
)
'Usage
Dim instance As ChannelConfiguration
Dim profileProperties As ReadOnlyCollection(Of ChannelProfileProperty)

instance.SetProfileProperties(profileProperties)
```

``` csharp
public void SetProfileProperties(
    ReadOnlyCollection<ChannelProfileProperty> profileProperties
)
```

``` c++
public:
void SetProfileProperties(
    ReadOnlyCollection<ChannelProfileProperty^>^ profileProperties
)
```

#### Parameters

  - profileProperties  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ChannelProfileProperty](channelprofileproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

