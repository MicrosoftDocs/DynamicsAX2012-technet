---
title: UpdateReturnQuantitiesDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: UpdateReturnQuantitiesDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateReturnQuantitiesDataRequest.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.updatereturnquantitiesdatarequest.updatereturnquantitiesdatarequest(v=AX.60)
ms:contentKeyID: 65319829
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.UpdateReturnQuantitiesDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# UpdateReturnQuantitiesDataRequest Constructor

Initializes a new instance of the [UpdateReturnQuantitiesDataRequest](updatereturnquantitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLines As IEnumerable(Of SalesLine) _
)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)

Dim instance As New UpdateReturnQuantitiesDataRequest(salesLines)
```

``` csharp
public UpdateReturnQuantitiesDataRequest(
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
UpdateReturnQuantitiesDataRequest(
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[UpdateReturnQuantitiesDataRequest Class](updatereturnquantitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

