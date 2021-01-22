---
title: ChannelManager.GetChannelTaxOverrides Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetChannelTaxOverrides Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelTaxOverrides(Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.channelmanager.getchanneltaxoverrides(v=AX.60)
ms:contentKeyID: 65315987
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ChannelManager.GetChannelTaxOverrides
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelTaxOverrides Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetChannelTaxOverrides ( _
    overrideBy As TaxOverrideBy, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of TaxOverride)
'Usage
Dim instance As ChannelManager
Dim overrideBy As TaxOverrideBy
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of TaxOverride)

returnValue = instance.GetChannelTaxOverrides(overrideBy, _
    settings)
```

``` csharp
public ReadOnlyCollection<TaxOverride> GetChannelTaxOverrides(
    TaxOverrideBy overrideBy,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<TaxOverride^>^ GetChannelTaxOverrides(
    TaxOverrideBy overrideBy, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - overrideBy  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxOverrideBy](taxoverrideby-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TaxOverride](taxoverride-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ChannelManager Class](channelmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

