---
title: GetButtonGridsResponse Constructor (IEnumerable(ButtonGrid)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetButtonGridsResponse Constructor (IEnumerable(ButtonGrid))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridsresponse.getbuttongridsresponse(v=AX.60)
ms:contentKeyID: 62205513
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetButtonGridsResponse Constructor (IEnumerable(ButtonGrid))

Initializes a new instance of the [GetButtonGridsResponse](getbuttongridsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    buttonGrids As IEnumerable(Of ButtonGrid) _
)
'Usage
Dim buttonGrids As IEnumerable(Of ButtonGrid)

Dim instance As New GetButtonGridsResponse(buttonGrids)
```

``` csharp
public GetButtonGridsResponse(
    IEnumerable<ButtonGrid> buttonGrids
)
```

``` c++
public:
GetButtonGridsResponse(
    IEnumerable<ButtonGrid^>^ buttonGrids
)
```

#### Parameters

  - buttonGrids  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetButtonGridsResponse Class](getbuttongridsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetButtonGridsResponse Overload](getbuttongridsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

