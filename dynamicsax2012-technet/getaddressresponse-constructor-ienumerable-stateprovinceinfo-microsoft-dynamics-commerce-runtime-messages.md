---
title: GetAddressResponse Constructor (IEnumerable(StateProvinceInfo)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAddressResponse Constructor (IEnumerable(StateProvinceInfo))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.StateProvinceInfo})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressresponse.getaddressresponse(v=AX.60)
ms:contentKeyID: 62215143
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressResponse Constructor (IEnumerable(StateProvinceInfo))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAddressResponse](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    stateProvinces As IEnumerable(Of StateProvinceInfo) _
)
'Usage
Dim stateProvinces As IEnumerable(Of StateProvinceInfo)

Dim instance As New GetAddressResponse(stateProvinces)
```

``` csharp
public GetAddressResponse(
    IEnumerable<StateProvinceInfo> stateProvinces
)
```

``` c++
public:
GetAddressResponse(
    IEnumerable<StateProvinceInfo^>^ stateProvinces
)
```

#### Parameters

  - stateProvinces  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[StateProvinceInfo](stateprovinceinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAddressResponse Class](getaddressresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAddressResponse Overload](getaddressresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

