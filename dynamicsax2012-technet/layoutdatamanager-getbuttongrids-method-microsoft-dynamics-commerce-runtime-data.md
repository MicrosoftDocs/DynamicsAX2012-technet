---
title: LayoutDataManager.GetButtonGrids Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetButtonGrids Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager.GetButtonGrids(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.layoutdatamanager.getbuttongrids(v=AX.60)
ms:contentKeyID: 65323085
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager.GetButtonGrids
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGrids Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonGrids ( _
    buttonGridsQuerySetting As QueryResultSettings _
) As PagedResult(Of ButtonGrid)
'Usage
Dim instance As LayoutDataManager
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

[LayoutDataManager Class](layoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

