---
title: GetProductCatalogAssociationsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductCatalogAssociationsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductcatalogassociationsdatarequest.getproductcatalogassociationsdatarequest(v=AX.60)
ms:contentKeyID: 65323246
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductCatalogAssociationsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductCatalogAssociationsDataRequest Constructor

Initializes a new instance of the [GetProductCatalogAssociationsDataRequest](getproductcatalogassociationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productIds As IEnumerable(Of Long) _
)
'Usage
Dim productIds As IEnumerable(Of Long)

Dim instance As New GetProductCatalogAssociationsDataRequest(productIds)
```

``` csharp
public GetProductCatalogAssociationsDataRequest(
    IEnumerable<long> productIds
)
```

``` c++
public:
GetProductCatalogAssociationsDataRequest(
    IEnumerable<long long>^ productIds
)
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[GetProductCatalogAssociationsDataRequest Class](getproductcatalogassociationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

