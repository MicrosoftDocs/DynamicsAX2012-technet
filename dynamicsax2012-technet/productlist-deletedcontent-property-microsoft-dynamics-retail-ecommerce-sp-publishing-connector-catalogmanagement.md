---
title: ProductList.DeletedContent Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: DeletedContent Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList.DeletedContent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlist.deletedcontent(v=AX.60)
ms:contentKeyID: 65316909
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductList.DeletedContent
dev_langs:
- CSharp
- C++
- VB
---

# DeletedContent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property DeletedContent As IDictionary(Of ProductListingKey, ProductListing)
    Get
    Private Set
'Usage
Dim instance As ProductList
Dim value As IDictionary(Of ProductListingKey, ProductListing)

value = instance.DeletedContent
```

``` csharp
public IDictionary<ProductListingKey, ProductListing> DeletedContent { get; private set; }
```

``` c++
public:
property IDictionary<ProductListingKey^, ProductListing^>^ DeletedContent {
    IDictionary<ProductListingKey^, ProductListing^>^ get ();
    private: void set (IDictionary<ProductListingKey^, ProductListing^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[ProductListingKey](productlistingkey-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md), [ProductListing](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

## See Also

#### Reference

[ProductList Class](productlist-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

