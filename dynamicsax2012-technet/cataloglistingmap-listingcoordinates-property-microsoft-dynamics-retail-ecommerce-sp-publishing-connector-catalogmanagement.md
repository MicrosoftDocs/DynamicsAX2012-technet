---
title: CatalogListingMap.ListingCoordinates Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: ListingCoordinates Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap.ListingCoordinates
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.cataloglistingmap.listingcoordinates(v=AX.60)
ms:contentKeyID: 65317661
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap.ListingCoordinates
dev_langs:
- CSharp
- C++
- VB
---

# ListingCoordinates Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property ListingCoordinates As IDictionary(Of KeyValuePair(Of Long, String), String)
    Get
'Usage
Dim instance As CatalogListingMap
Dim value As IDictionary(Of KeyValuePair(Of Long, String), String)

value = instance.ListingCoordinates
```

``` csharp
public IDictionary<KeyValuePair<long, string>, string> ListingCoordinates { get; }
```

``` c++
public:
property IDictionary<KeyValuePair<long long, String^>, String^>^ ListingCoordinates {
    IDictionary<KeyValuePair<long long, String^>, String^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[KeyValuePair](https://technet.microsoft.com/library/5tbh8a42\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>, [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[CatalogListingMap Class](cataloglistingmap-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

