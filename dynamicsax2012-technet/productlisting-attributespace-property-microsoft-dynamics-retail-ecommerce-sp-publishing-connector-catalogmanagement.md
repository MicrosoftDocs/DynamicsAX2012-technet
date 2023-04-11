---
title: ProductListing.AttributeSpace Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: AttributeSpace Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.AttributeSpace
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlisting.attributespace(v=AX.60)
ms:contentKeyID: 65318085
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.AttributeSpace
dev_langs:
- CSharp
- C++
- VB
---

# AttributeSpace Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Property AttributeSpace As IDictionary(Of String, AttributeProductListing)
    Get
    Private Set
'Usage
Dim instance As ProductListing
Dim value As IDictionary(Of String, AttributeProductListing)

value = instance.AttributeSpace
```

``` csharp
public IDictionary<string, AttributeProductListing> AttributeSpace { get; private set; }
```

``` c++
public:
property IDictionary<String^, AttributeProductListing^>^ AttributeSpace {
    IDictionary<String^, AttributeProductListing^>^ get ();
    private: void set (IDictionary<String^, AttributeProductListing^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [AttributeProductListing](attributeproductlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

## See Also

#### Reference

[ProductListing Class](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

