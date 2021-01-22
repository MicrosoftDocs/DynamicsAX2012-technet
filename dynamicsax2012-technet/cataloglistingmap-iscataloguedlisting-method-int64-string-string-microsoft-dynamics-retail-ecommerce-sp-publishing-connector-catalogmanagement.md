---
title: CatalogListingMap.IsCataloguedListing Method (Int64, String, String) (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: IsCataloguedListing Method (Int64, String, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.CatalogListingMap.IsCataloguedListing(System.Int64,System.String,System.String@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.cataloglistingmap.iscataloguedlisting(v=AX.60)
ms:contentKeyID: 65317327
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IsCataloguedListing Method (Int64, String, String)

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Function IsCataloguedListing ( _
    listingId As Long, _
    languageId As String, _
    <OutAttribute> ByRef containerListId As String _
) As Boolean
'Usage
Dim instance As CatalogListingMap
Dim listingId As Long
Dim languageId As String
Dim containerListId As String
Dim returnValue As Boolean

returnValue = instance.IsCataloguedListing(listingId, _
    languageId, containerListId)
```

``` csharp
public bool IsCataloguedListing(
    long listingId,
    string languageId,
    out string containerListId
)
```

``` c++
public:
bool IsCataloguedListing(
    long long listingId, 
    String^ languageId, 
    [OutAttribute] String^% containerListId
)
```

#### Parameters

  - listingId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - languageId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - containerListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CatalogListingMap Class](cataloglistingmap-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[IsCataloguedListing Overload](cataloglistingmap-iscataloguedlisting-method-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

