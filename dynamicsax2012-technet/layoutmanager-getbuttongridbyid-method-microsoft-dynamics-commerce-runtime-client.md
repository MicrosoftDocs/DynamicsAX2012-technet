---
title: LayoutManager.GetButtonGridById Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetButtonGridById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.GetButtonGridById(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.layoutmanager.getbuttongridbyid(v=AX.60)
ms:contentKeyID: 65315889
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LayoutManager.GetButtonGridById
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridById Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetButtonGridById ( _
    buttonGridId As String, _
    buttonsSettings As QueryResultSettings _
) As ButtonGrid
'Usage
Dim instance As LayoutManager
Dim buttonGridId As String
Dim buttonsSettings As QueryResultSettings
Dim returnValue As ButtonGrid

returnValue = instance.GetButtonGridById(buttonGridId, _
    buttonsSettings)
```

``` csharp
public ButtonGrid GetButtonGridById(
    string buttonGridId,
    QueryResultSettings buttonsSettings
)
```

``` c++
public:
ButtonGrid^ GetButtonGridById(
    String^ buttonGridId, 
    QueryResultSettings^ buttonsSettings
)
```

#### Parameters

  - buttonGridId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - buttonsSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[LayoutManager Class](layoutmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

