---
title: CatalogListingMap.GetListForListing Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: GetListForListing Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap.GetListForListing(System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.cataloglistingmap.getlistforlisting(v=AX.60)
ms:contentKeyID: 65316975
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap.GetListForListing
dev_langs:
- CSharp
- C++
- VB
---

# GetListForListing Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Function GetListForListing ( _
    listingId As Long, _
    languageId As String _
) As String
'Usage
Dim instance As CatalogListingMap
Dim listingId As Long
Dim languageId As String
Dim returnValue As String

returnValue = instance.GetListForListing(listingId, _
    languageId)
```

``` csharp
public string GetListForListing(
    long listingId,
    string languageId
)
```

``` c++
public:
String^ GetListForListing(
    long long listingId, 
    String^ languageId
)
```

#### Parameters

  - listingId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CatalogListingMap Class](cataloglistingmap-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

