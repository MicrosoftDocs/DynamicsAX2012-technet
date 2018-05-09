---
title: GetLinkedProductsDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetLinkedProductsDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLinkedProductsDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.LinkedProduct})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getlinkedproductsdataresponse.getlinkedproductsdataresponse(v=AX.60)
ms:contentKeyID: 65319000
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetLinkedProductsDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLinkedProductsDataResponse Constructor

Initializes a new instance of the [GetLinkedProductsDataResponse](getlinkedproductsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    linkedProducts As ReadOnlyCollection(Of LinkedProduct) _
)
'Usage
Dim linkedProducts As ReadOnlyCollection(Of LinkedProduct)

Dim instance As New GetLinkedProductsDataResponse(linkedProducts)
```

``` csharp
public GetLinkedProductsDataResponse(
    ReadOnlyCollection<LinkedProduct> linkedProducts
)
```

``` c++
public:
GetLinkedProductsDataResponse(
    ReadOnlyCollection<LinkedProduct^>^ linkedProducts
)
```

#### Parameters

  - linkedProducts  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetLinkedProductsDataResponse Class](getlinkedproductsdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

