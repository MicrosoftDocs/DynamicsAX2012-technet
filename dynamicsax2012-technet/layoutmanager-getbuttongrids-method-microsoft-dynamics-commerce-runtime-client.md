---
title: LayoutManager.GetButtonGrids Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetButtonGrids Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.GetButtonGrids(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.layoutmanager.getbuttongrids(v=AX.60)
ms:contentKeyID: 65316441
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.GetButtonGrids
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGrids Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonGrids ( _
    buttonGridsQuerySetting As QueryResultSettings _
) As PagedResult(Of ButtonGrid)
'Usage
Dim instance As LayoutManager
Dim buttonGridsQuerySetting As QueryResultSettings
Dim returnValue As PagedResult(Of ButtonGrid)

returnValue = instance.GetButtonGrids(buttonGridsQuerySetting)
```

``` csharp
public PagedResult<ButtonGrid> GetButtonGrids(
    QueryResultSettings buttonGridsQuerySetting
)
```

``` c++
public:
PagedResult<ButtonGrid^>^ GetButtonGrids(
    QueryResultSettings^ buttonGridsQuerySetting
)
```

#### Parameters

  - buttonGridsQuerySetting  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[LayoutManager Class](layoutmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

