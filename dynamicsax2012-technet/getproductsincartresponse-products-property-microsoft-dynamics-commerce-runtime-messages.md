---
title: GetProductsInCartResponse.Products Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Products Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductsInCartResponse.Products
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getproductsincartresponse.products(v=AX.60)
ms:contentKeyID: 62214794
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductsInCartResponse.Products
dev_langs:
- CSharp
- C++
- VB
---

# Products Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the list of products used in context of the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Products As ReadOnlyCollection(Of Product)
    Get
    Private Set
'Usage
Dim instance As GetProductsInCartResponse
Dim value As ReadOnlyCollection(Of Product)

value = instance.Products
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Product> Products { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Product^>^ Products {
    ReadOnlyCollection<Product^>^ get ();
    private: void set (ReadOnlyCollection<Product^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductsInCartResponse Class](getproductsincartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

