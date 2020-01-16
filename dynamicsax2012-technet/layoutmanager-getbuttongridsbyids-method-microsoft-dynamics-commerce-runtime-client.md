---
title: LayoutManager.GetButtonGridsByIds Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetButtonGridsByIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.GetButtonGridsByIds(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.layoutmanager.getbuttongridsbyids(v=AX.60)
ms:contentKeyID: 65319674
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.GetButtonGridsByIds
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridsByIds Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonGridsByIds ( _
    buttonGridIds As IEnumerable(Of String), _
    buttonGridsQuerySetting As QueryResultSettings _
) As PagedResult(Of ButtonGrid)
'Usage
Dim instance As LayoutManager
Dim buttonGridIds As IEnumerable(Of String)
Dim buttonGridsQuerySetting As QueryResultSettings
Dim returnValue As PagedResult(Of ButtonGrid)

returnValue = instance.GetButtonGridsByIds(buttonGridIds, _
    buttonGridsQuerySetting)
```

``` csharp
public PagedResult<ButtonGrid> GetButtonGridsByIds(
    IEnumerable<string> buttonGridIds,
    QueryResultSettings buttonGridsQuerySetting
)
```

``` c++
public:
PagedResult<ButtonGrid^>^ GetButtonGridsByIds(
    IEnumerable<String^>^ buttonGridIds, 
    QueryResultSettings^ buttonGridsQuerySetting
)
```

#### Parameters

  - buttonGridIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - buttonGridsQuerySetting  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[LayoutManager Class](layoutmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

