---
title: IPosCustomControlV1.LoadLayout Method  (Microsoft.Dynamics.Retail.Pos.Contracts.UI)
TOCTitle: LoadLayout Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.UI.IPosCustomControlV1.LoadLayout(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.ui.iposcustomcontrolv1.loadlayout(v=AX.60)
ms:contentKeyID: 49844575
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.UI.IPosCustomControlV1.LoadLayout
dev_langs:
- CSharp
- C++
- VB
---

# LoadLayout Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Load layout.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.UI](microsoft-dynamics-retail-pos-contracts-ui-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub LoadLayout ( _
    layoutId As String _
)
'Usage
Dim instance As IPosCustomControlV1
Dim layoutId As String

instance.LoadLayout(layoutId)
```

``` csharp
void LoadLayout(
    string layoutId
)
```

``` c++
void LoadLayout(
    String^ layoutId
)
```

#### Parameters

  - layoutId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## Remarks

Called when new layout is being loaded. e.g. during operator log on.

## See Also

#### Reference

[IPosCustomControlV1 Interface](iposcustomcontrolv1-interface-microsoft-dynamics-retail-pos-contracts-ui.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.UI Namespace](microsoft-dynamics-retail-pos-contracts-ui-namespace.md)

