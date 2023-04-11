---
title: ProductList.Content Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: Content Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList.Content
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlist.content(v=AX.60)
ms:contentKeyID: 65316653
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList.Content
dev_langs:
- CSharp
- C++
- VB
---

# Content Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property Content As IDictionary(Of ProductListingKey, IList(Of ProductListing))
    Get
    Private Set
'Usage
Dim instance As ProductList
Dim value As IDictionary(Of ProductListingKey, IList(Of ProductListing))

value = instance.Content
```

``` csharp
public IDictionary<ProductListingKey, IList<ProductListing>> Content { get; private set; }
```

``` c++
public:
property IDictionary<ProductListingKey^, IList<ProductListing^>^>^ Content {
    IDictionary<ProductListingKey^, IList<ProductListing^>^>^ get ();
    private: void set (IDictionary<ProductListingKey^, IList<ProductListing^>^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[ProductListingKey](productlistingkey-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md), [IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>\>  

## See Also

#### Reference

[ProductList Class](productlist-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

