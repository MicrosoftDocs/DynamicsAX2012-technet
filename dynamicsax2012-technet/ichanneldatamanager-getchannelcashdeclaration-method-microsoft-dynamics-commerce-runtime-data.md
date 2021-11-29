---
title: IChannelDataManager.GetChannelCashDeclaration Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetChannelCashDeclaration Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelCashDeclaration(System.Int64,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getchannelcashdeclaration(v=AX.60)
ms:contentKeyID: 65322149
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetChannelCashDeclaration
dev_langs:
- CSharp
- C++
- VB
---

# GetChannelCashDeclaration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetChannelCashDeclaration ( _
    channelId As Long, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of CashDeclaration)
'Usage
Dim instance As IChannelDataManager
Dim channelId As Long
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of CashDeclaration)

returnValue = instance.GetChannelCashDeclaration(channelId, _
    settings)
```

``` csharp
ReadOnlyCollection<CashDeclaration> GetChannelCashDeclaration(
    long channelId,
    QueryResultSettings settings
)
```

``` c++
ReadOnlyCollection<CashDeclaration^>^ GetChannelCashDeclaration(
    long long channelId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[CashDeclaration](cashdeclaration-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

