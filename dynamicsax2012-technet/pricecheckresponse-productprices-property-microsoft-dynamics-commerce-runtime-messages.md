---
title: PriceCheckResponse.ProductPrices Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ProductPrices Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckResponse.ProductPrices
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pricecheckresponse.productprices(v=AX.60)
ms:contentKeyID: 62214965
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckResponse.ProductPrices
dev_langs:
- CSharp
- C++
- VB
---

# ProductPrices Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of item prices.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductPrices As ReadOnlyCollection(Of ProductPrice)
    Get
    Private Set
'Usage
Dim instance As PriceCheckResponse
Dim value As ReadOnlyCollection(Of ProductPrice)

value = instance.ProductPrices
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ProductPrice> ProductPrices { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductPrice^>^ ProductPrices {
    ReadOnlyCollection<ProductPrice^>^ get ();
    private: void set (ReadOnlyCollection<ProductPrice^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[PriceCheckResponse Class](pricecheckresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

