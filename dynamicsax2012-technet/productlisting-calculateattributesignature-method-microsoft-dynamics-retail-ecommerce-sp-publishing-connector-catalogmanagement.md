---
title: ProductListing.CalculateAttributeSignature Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: CalculateAttributeSignature Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.CalculateAttributeSignature(System.Collections.Generic.IDictionary{System.String,Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.AttributeProductListing})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.productlisting.calculateattributesignature(v=AX.60)
ms:contentKeyID: 65318402
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ProductListing.CalculateAttributeSignature
dev_langs:
- CSharp
- C++
- VB
---

# CalculateAttributeSignature Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Sub CalculateAttributeSignature ( _
    attributeSpace As IDictionary(Of String, AttributeProductListing) _
)
'Usage
Dim instance As ProductListing
Dim attributeSpace As IDictionary(Of String, AttributeProductListing)

instance.CalculateAttributeSignature(attributeSpace)
```

``` csharp
public void CalculateAttributeSignature(
    IDictionary<string, AttributeProductListing> attributeSpace
)
```

``` c++
public:
virtual void CalculateAttributeSignature(
    IDictionary<String^, AttributeProductListing^>^ attributeSpace
) sealed
```

#### Parameters

  - attributeSpace  
    Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [AttributeProductListing](attributeproductlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

#### Implements

[IProductListingAttributeSignature.CalculateAttributeSignature(IDictionary\<String, AttributeProductListing\>)](iproductlistingattributesignature-calculateattributesignature-method-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

## See Also

#### Reference

[ProductListing Class](productlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

