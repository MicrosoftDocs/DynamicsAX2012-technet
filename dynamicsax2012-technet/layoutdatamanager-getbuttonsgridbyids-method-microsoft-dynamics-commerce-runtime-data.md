---
title: LayoutDataManager.GetButtonsGridByIds Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetButtonsGridByIds Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager.GetButtonsGridByIds(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.layoutdatamanager.getbuttonsgridbyids(v=AX.60)
ms:contentKeyID: 62205910
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager.GetButtonsGridByIds
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonsGridByIds Method

Gets a buttongrids by identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonsGridByIds ( _
    buttonGridIds As IEnumerable(Of String) _
) As PagedResult(Of ButtonGrid)
'Usage
Dim instance As LayoutDataManager
Dim buttonGridIds As IEnumerable(Of String)
Dim returnValue As PagedResult(Of ButtonGrid)

returnValue = instance.GetButtonsGridByIds(buttonGridIds)
```

``` csharp
public PagedResult<ButtonGrid> GetButtonsGridByIds(
    IEnumerable<string> buttonGridIds
)
```

``` c++
public:
PagedResult<ButtonGrid^>^ GetButtonsGridByIds(
    IEnumerable<String^>^ buttonGridIds
)
```

#### Parameters

  - buttonGridIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Collection of matching buttongrids.  

## See Also

#### Reference

[LayoutDataManager Class](layoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

