---
title: GetButtonGridsServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetButtonGridsServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGrid})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridsserviceresponse.getbuttongridsserviceresponse(v=AX.60)
ms:contentKeyID: 62209777
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridsServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetButtonGridsServiceResponse Constructor

Initializes a new instance of the [GetButtonGridsServiceResponse](getbuttongridsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    buttonGrids As IEnumerable(Of ButtonGrid) _
)
'Usage
Dim buttonGrids As IEnumerable(Of ButtonGrid)

Dim instance As New GetButtonGridsServiceResponse(buttonGrids)
```

``` csharp
public GetButtonGridsServiceResponse(
    IEnumerable<ButtonGrid> buttonGrids
)
```

``` c++
public:
GetButtonGridsServiceResponse(
    IEnumerable<ButtonGrid^>^ buttonGrids
)
```

#### Parameters

  - buttonGrids  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ButtonGrid](buttongrid-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetButtonGridsServiceResponse Class](getbuttongridsserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

