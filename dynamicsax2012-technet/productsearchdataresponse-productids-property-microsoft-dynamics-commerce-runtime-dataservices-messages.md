---
title: ProductSearchDataResponse.ProductIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ProductIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataResponse.ProductIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.productsearchdataresponse.productids(v=AX.60)
ms:contentKeyID: 65322645
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataResponse.ProductIds
dev_langs:
- CSharp
- C++
- VB
---

# ProductIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of product identifiers found in the search.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property ProductIds As ICollection(Of Long)
    Get
    Private Set
'Usage
Dim instance As ProductSearchDataResponse
Dim value As ICollection(Of Long)

value = instance.ProductIds
```

``` csharp
public ICollection<long> ProductIds { get; private set; }
```

``` c++
public:
property ICollection<long long>^ ProductIds {
    ICollection<long long>^ get ();
    private: void set (ICollection<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchDataResponse Class](productsearchdataresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

