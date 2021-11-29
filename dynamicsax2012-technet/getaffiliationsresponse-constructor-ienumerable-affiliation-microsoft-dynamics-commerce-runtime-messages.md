---
title: GetAffiliationsResponse Constructor (IEnumerable(Affiliation)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAffiliationsResponse Constructor (IEnumerable(Affiliation))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAffiliationsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Affiliation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaffiliationsresponse.getaffiliationsresponse(v=AX.60)
ms:contentKeyID: 62211421
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAffiliationsResponse Constructor (IEnumerable(Affiliation))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAffiliationsResponse](getaffiliationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    affiliations As IEnumerable(Of Affiliation) _
)
'Usage
Dim affiliations As IEnumerable(Of Affiliation)

Dim instance As New GetAffiliationsResponse(affiliations)
```

``` csharp
public GetAffiliationsResponse(
    IEnumerable<Affiliation> affiliations
)
```

``` c++
public:
GetAffiliationsResponse(
    IEnumerable<Affiliation^>^ affiliations
)
```

#### Parameters

  - affiliations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Affiliation](affiliation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetAffiliationsResponse Class](getaffiliationsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetAffiliationsResponse Overload](getaffiliationsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

