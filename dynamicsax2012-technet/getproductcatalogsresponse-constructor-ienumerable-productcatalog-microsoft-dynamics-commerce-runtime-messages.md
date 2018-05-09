---
title: GetProductCatalogsResponse Constructor (IEnumerable(ProductCatalog)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetProductCatalogsResponse Constructor (IEnumerable(ProductCatalog))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductCatalogsResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getproductcatalogsresponse.getproductcatalogsresponse(v=AX.60)
ms:contentKeyID: 62211433
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductCatalogsResponse Constructor (IEnumerable(ProductCatalog))

Initializes a new instance of the [GetProductCatalogsResponse](getproductcatalogsresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    catalogs As IEnumerable(Of ProductCatalog) _
)
'Usage
Dim catalogs As IEnumerable(Of ProductCatalog)

Dim instance As New GetProductCatalogsResponse(catalogs)
```

``` csharp
public GetProductCatalogsResponse(
    IEnumerable<ProductCatalog> catalogs
)
```

``` c++
public:
GetProductCatalogsResponse(
    IEnumerable<ProductCatalog^>^ catalogs
)
```

#### Parameters

  - catalogs  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetProductCatalogsResponse Class](getproductcatalogsresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetProductCatalogsResponse Overload](getproductcatalogsresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

