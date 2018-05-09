---
title: GetItemAvailabilitiesResponse Constructor (IEnumerable(ItemAvailability)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetItemAvailabilitiesResponse Constructor (IEnumerable(ItemAvailability))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetItemAvailabilitiesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getitemavailabilitiesresponse.getitemavailabilitiesresponse(v=AX.60)
ms:contentKeyID: 49848162
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemAvailabilitiesResponse Constructor (IEnumerable(ItemAvailability))

Initializes a new instance of the [GetItemAvailabilitiesResponse](getitemavailabilitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemAvailabilities As IEnumerable(Of ItemAvailability) _
)
'Usage
Dim itemAvailabilities As IEnumerable(Of ItemAvailability)

Dim instance As New GetItemAvailabilitiesResponse(itemAvailabilities)
```

``` csharp
public GetItemAvailabilitiesResponse(
    IEnumerable<ItemAvailability> itemAvailabilities
)
```

``` c++
public:
GetItemAvailabilitiesResponse(
    IEnumerable<ItemAvailability^>^ itemAvailabilities
)
```

#### Parameters

  - itemAvailabilities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetItemAvailabilitiesResponse Class](getitemavailabilitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetItemAvailabilitiesResponse Overload](getitemavailabilitiesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

