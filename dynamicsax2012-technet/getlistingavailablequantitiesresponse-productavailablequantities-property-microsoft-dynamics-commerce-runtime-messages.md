---
title: GetListingAvailableQuantitiesResponse.ProductAvailableQuantities Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: ProductAvailableQuantities Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingAvailableQuantitiesResponse.ProductAvailableQuantities
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlistingavailablequantitiesresponse.productavailablequantities(v=AX.60)
ms:contentKeyID: 62212628
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingAvailableQuantitiesResponse.ProductAvailableQuantities
dev_langs:
- CSharp
- C++
- VB
---

# ProductAvailableQuantities Property

Gets the collection of item available quantities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductAvailableQuantities As ReadOnlyCollection(Of ProductAvailableQuantity)
    Get
    Private Set
'Usage
Dim instance As GetListingAvailableQuantitiesResponse
Dim value As ReadOnlyCollection(Of ProductAvailableQuantity)

value = instance.ProductAvailableQuantities
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<ProductAvailableQuantity> ProductAvailableQuantities { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<ProductAvailableQuantity^>^ ProductAvailableQuantities {
    ReadOnlyCollection<ProductAvailableQuantity^>^ get ();
    private: void set (ReadOnlyCollection<ProductAvailableQuantity^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductAvailableQuantity](productavailablequantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetListingAvailableQuantitiesResponse Class](getlistingavailablequantitiesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

