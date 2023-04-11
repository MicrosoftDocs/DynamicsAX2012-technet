---
title: DatabaseAccessor.ChannelConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ChannelConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ChannelConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.databaseaccessor.channelconfiguration(v=AX.60)
ms:contentKeyID: 62212134
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.DatabaseAccessor.ChannelConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# ChannelConfiguration Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Property ChannelConfiguration As ChannelConfiguration
    Get
    Private Set
'Usage
Dim value As ChannelConfiguration

value = Me.ChannelConfiguration
```

``` csharp
protected ChannelConfiguration ChannelConfiguration { get; private set; }
```

``` c++
protected:
property ChannelConfiguration^ ChannelConfiguration {
    ChannelConfiguration^ get ();
    private: void set (ChannelConfiguration^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChannelConfiguration](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[DatabaseAccessor Class](databaseaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

