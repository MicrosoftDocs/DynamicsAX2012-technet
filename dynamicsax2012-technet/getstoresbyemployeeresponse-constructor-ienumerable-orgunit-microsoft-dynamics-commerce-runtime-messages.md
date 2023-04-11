---
title: GetStoresByEmployeeResponse Constructor (IEnumerable(OrgUnit)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoresByEmployeeResponse Constructor (IEnumerable(OrgUnit))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresByEmployeeResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoresbyemployeeresponse.getstoresbyemployeeresponse(v=AX.60)
ms:contentKeyID: 62202810
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoresByEmployeeResponse Constructor (IEnumerable(OrgUnit))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetStoresByEmployeeResponse](getstoresbyemployeeresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

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

Dim instance As New GetStoresByEmployeeResponse(stores)
```

``` csharp
public GetStoresByEmployeeResponse(
    IEnumerable<OrgUnit> stores
)
```

``` c++
public:
GetStoresByEmployeeResponse(
    IEnumerable<OrgUnit^>^ stores
)
```

#### Parameters

  - stores  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetStoresByEmployeeResponse Class](getstoresbyemployeeresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoresByEmployeeResponse Overload](getstoresbyemployeeresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

