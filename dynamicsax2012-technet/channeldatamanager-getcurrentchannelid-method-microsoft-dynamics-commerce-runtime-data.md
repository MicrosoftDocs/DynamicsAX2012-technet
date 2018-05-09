---
title: ChannelDataManager.GetCurrentChannelId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetCurrentChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetCurrentChannelId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.channeldatamanager.getcurrentchannelid(v=AX.60)
ms:contentKeyID: 49846064
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ChannelDataManager.GetCurrentChannelId
dev_langs:
- CSharp
- C++
- VB
---

# GetCurrentChannelId Method

Gets the current channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetCurrentChannelId As Long
'Usage
Dim instance As ChannelDataManager
Dim returnValue As Long

returnValue = instance.GetCurrentChannelId()
```

``` csharp
public long GetCurrentChannelId()
```

``` c++
public:
virtual long long GetCurrentChannelId() sealed
```

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  
The channel identifier or 0 if no channel is found.  

#### Implements

[IChannelDataManager.GetCurrentChannelId()](ichanneldatamanager-getcurrentchannelid-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ChannelDataManager Class](channeldatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

