---
title: GetButtonGridsByIdsResponse Constructor (IEnumerable(ButtonGrid)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetButtonGridsByIdsResponse Constructor (IEnumerable(ButtonGrid))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetButtonGridsByIdsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getbuttongridsbyidsresponse.getbuttongridsbyidsresponse(v=AX.60)
ms:contentKeyID: 62212954
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetButtonGridsByIdsResponse Constructor (IEnumerable(ButtonGrid))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetButtonGridsByIdsResponse](getbuttongridsbyidsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

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

Dim instance As New GetButtonGridsByIdsResponse(buttonGrids)
```

``` csharp
public GetButtonGridsByIdsResponse(
    IEnumerable<ButtonGrid> buttonGrids
)
```

``` c++
public:
GetButtonGridsByIdsResponse(
    IEnumerable<ButtonGrid^>^ buttonGrids
)
```

#### Parameters

  - buttonGrids  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetButtonGridsByIdsResponse Class](getbuttongridsbyidsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetButtonGridsByIdsResponse Overload](getbuttongridsbyidsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

