---
title: GetProductRefinersDataResponse.Refiners Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Refiners Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataResponse.Refiners
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductrefinersdataresponse.refiners(v=AX.60)
ms:contentKeyID: 65321498
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataResponse.Refiners
dev_langs:
- CSharp
- C++
- VB
---

# Refiners Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of product refiners.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Refiners As ReadOnlyCollection(Of ProductRefiner)
    Get
    Private Set
'Usage
Dim instance As GetProductRefinersDataResponse
Dim value As ReadOnlyCollection(Of ProductRefiner)

value = instance.Refiners
```

``` csharp
public ReadOnlyCollection<ProductRefiner> Refiners { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductRefiner^>^ Refiners {
    ReadOnlyCollection<ProductRefiner^>^ get ();
    private: void set (ReadOnlyCollection<ProductRefiner^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRefiner](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductRefinersDataResponse Class](getproductrefinersdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

