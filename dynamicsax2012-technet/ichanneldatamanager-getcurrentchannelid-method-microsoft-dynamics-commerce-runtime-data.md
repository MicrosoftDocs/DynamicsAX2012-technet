---
title: IChannelDataManager.GetCurrentChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrentChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetCurrentChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.ichanneldatamanager.getcurrentchannelid(v=AX.60)
ms:contentKeyID: 62208448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IChannelDataManager.GetCurrentChannelId
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentChannelId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the identifier of the current channel, or 0 if no channel is found.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Function GetCurrentChannelId As Long
'Usage
Dim instance As IChannelDataManager
Dim returnValue As Long

returnValue = instance.GetCurrentChannelId()
```

``` csharp
long GetCurrentChannelId()
```

``` c++
long long GetCurrentChannelId()
```

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The identifier of the current channel, or 0 if no channel is configured.  

## See Also

#### Reference

[IChannelDataManager Interface](ichanneldatamanager-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

