---
title: TillLayoutDataManager.GetTillLayout Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTillLayout Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TillLayoutDataManager.GetTillLayout(System.Int64,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.tilllayoutdatamanager.gettilllayout(v=AX.60)
ms:contentKeyID: 65316261
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TillLayoutDataManager.GetTillLayout
dev_langs:
- CSharp
- C++
- VB
---

# GetTillLayout Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTillLayout ( _
    channelId As Long, _
    terminalId As Long, _
    userId As String _
) As TillLayout
'Usage
Dim instance As TillLayoutDataManager
Dim channelId As Long
Dim terminalId As Long
Dim userId As String
Dim returnValue As TillLayout

returnValue = instance.GetTillLayout(channelId, _
    terminalId, userId)
```

``` csharp
public TillLayout GetTillLayout(
    long channelId,
    long terminalId,
    string userId
)
```

``` c++
public:
TillLayout^ GetTillLayout(
    long long channelId, 
    long long terminalId, 
    String^ userId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - userId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[TillLayoutDataManager Class](tilllayoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

