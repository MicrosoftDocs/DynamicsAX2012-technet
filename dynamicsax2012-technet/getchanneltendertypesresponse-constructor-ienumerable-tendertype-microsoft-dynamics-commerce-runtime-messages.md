---
title: GetChannelTenderTypesResponse Constructor (IEnumerable(TenderType)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelTenderTypesResponse Constructor (IEnumerable(TenderType))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelTenderTypesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchanneltendertypesresponse.getchanneltendertypesresponse(v=AX.60)
ms:contentKeyID: 62213325
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelTenderTypesResponse Constructor (IEnumerable(TenderType))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetChannelTenderTypesResponse](getchanneltendertypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    tenderTypes As IEnumerable(Of TenderType) _
)
'Usage
Dim tenderTypes As IEnumerable(Of TenderType)

Dim instance As New GetChannelTenderTypesResponse(tenderTypes)
```

``` csharp
public GetChannelTenderTypesResponse(
    IEnumerable<TenderType> tenderTypes
)
```

``` c++
public:
GetChannelTenderTypesResponse(
    IEnumerable<TenderType^>^ tenderTypes
)
```

#### Parameters

  - tenderTypes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[TenderType](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelTenderTypesResponse Class](getchanneltendertypesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelTenderTypesResponse Overload](getchanneltendertypesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

