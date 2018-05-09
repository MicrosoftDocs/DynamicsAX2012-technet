---
title: ProductListingKey Constructor (Int64, Int64, String) (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector)
TOCTitle: ProductListingKey Constructor (Int64, Int64, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.ProductListingKey.#ctor(System.Int64,System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.productlistingkey.productlistingkey(v=AX.60)
ms:contentKeyID: 65316882
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductListingKey Constructor (Int64, Int64, String)

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productListingId As Long, _
    productCatalogId As Long, _
    productLanguageTag As String _
)
'Usage
Dim productListingId As Long
Dim productCatalogId As Long
Dim productLanguageTag As String

Dim instance As New ProductListingKey(productListingId, _
    productCatalogId, productLanguageTag)
```

``` csharp
public ProductListingKey(
    long productListingId,
    long productCatalogId,
    string productLanguageTag
)
```

``` c++
public:
ProductListingKey(
    long long productListingId, 
    long long productCatalogId, 
    String^ productLanguageTag
)
```

#### Parameters

  - productListingId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - productCatalogId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - productLanguageTag  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ProductListingKey Class](productlistingkey-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[ProductListingKey Overload](productlistingkey-constructor-microsoft-dynamics-retail-ecommerce-sp-publishing-connector.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-namespace.md)

