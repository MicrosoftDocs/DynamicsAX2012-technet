---
title: GetAvailableStoresResponse Constructor (IEnumerable(OrgUnit)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAvailableStoresResponse Constructor (IEnumerable(OrgUnit))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAvailableStoresResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getavailablestoresresponse.getavailablestoresresponse(v=AX.60)
ms:contentKeyID: 62205865
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAvailableStoresResponse Constructor (IEnumerable(OrgUnit))

Initializes a new instance of the [GetAvailableStoresResponse](getavailablestoresresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    stores As IEnumerable(Of OrgUnit) _
)
'Usage
Dim stores As IEnumerable(Of OrgUnit)

Dim instance As New GetAvailableStoresResponse(stores)
```

``` csharp
public GetAvailableStoresResponse(
    IEnumerable<OrgUnit> stores
)
```

``` c++
public:
GetAvailableStoresResponse(
    IEnumerable<OrgUnit^>^ stores
)
```

#### Parameters

  - stores  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAvailableStoresResponse Class](getavailablestoresresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAvailableStoresResponse Overload](getavailablestoresresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

