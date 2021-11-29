---
title: LayoutDataManager.GetButtonGridById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetButtonGridById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager.GetButtonGridById(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.layoutdatamanager.getbuttongridbyid(v=AX.60)
ms:contentKeyID: 62202421
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.LayoutDataManager.GetButtonGridById
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a buttongrid by its identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonGridById ( _
    buttonGridId As String _
) As ButtonGrid
'Usage
Dim instance As LayoutDataManager
Dim buttonGridId As String
Dim returnValue As ButtonGrid

returnValue = instance.GetButtonGridById(buttonGridId)
```

``` csharp
public ButtonGrid GetButtonGridById(
    string buttonGridId
)
```

``` c++
public:
ButtonGrid^ GetButtonGridById(
    String^ buttonGridId
)
```

#### Parameters

  - buttonGridId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
A buttongrid.  

## See Also

#### Reference

[LayoutDataManager Class](layoutdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

