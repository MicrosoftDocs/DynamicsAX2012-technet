---
title: GetStoresResponse Constructor (PagedResult(OrgUnit)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoresResponse Constructor (PagedResult(OrgUnit))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresResponse.#ctor(Microsoft.Dynamics.Commerce.Runtime.PagedResult{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoresresponse.getstoresresponse(v=AX.60)
ms:contentKeyID: 62212219
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoresResponse Constructor (PagedResult(OrgUnit))

Initializes a new instance of the [GetStoresResponse](getstoresresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    stores As PagedResult(Of OrgUnit) _
)
'Usage
Dim stores As PagedResult(Of OrgUnit)

Dim instance As New GetStoresResponse(stores)
```

``` csharp
public GetStoresResponse(
    PagedResult<OrgUnit> stores
)
```

``` c++
public:
GetStoresResponse(
    PagedResult<OrgUnit^>^ stores
)
```

#### Parameters

  - stores  
    Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStoresResponse Class](getstoresresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoresResponse Overload](getstoresresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

