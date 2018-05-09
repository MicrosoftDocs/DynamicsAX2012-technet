---
title: GetProductRefinersDataResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetProductRefinersDataResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataResponse.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner},System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductrefinersdataresponse.getproductrefinersdataresponse(v=AX.60)
ms:contentKeyID: 65322534
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductRefinersDataResponse Constructor

Initializes a new instance of the [GetProductRefinersDataResponse](getproductrefinersdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    refiners As ReadOnlyCollection(Of ProductRefiner), _
    refinerValues As ReadOnlyCollection(Of ProductRefinerValue) _
)
'Usage
Dim refiners As ReadOnlyCollection(Of ProductRefiner)
Dim refinerValues As ReadOnlyCollection(Of ProductRefinerValue)

Dim instance As New GetProductRefinersDataResponse(refiners, _
    refinerValues)
```

``` csharp
public GetProductRefinersDataResponse(
    ReadOnlyCollection<ProductRefiner> refiners,
    ReadOnlyCollection<ProductRefinerValue> refinerValues
)
```

``` c++
public:
GetProductRefinersDataResponse(
    ReadOnlyCollection<ProductRefiner^>^ refiners, 
    ReadOnlyCollection<ProductRefinerValue^>^ refinerValues
)
```

#### Parameters

  - refiners  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductRefiner](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - refinerValues  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductRefinerValue](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductRefinersDataResponse Class](getproductrefinersdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

