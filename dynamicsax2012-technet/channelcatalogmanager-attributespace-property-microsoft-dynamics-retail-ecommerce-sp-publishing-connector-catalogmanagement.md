---
title: ChannelCatalogManager.AttributeSpace Property  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: AttributeSpace Property
ms:assetid: P:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.AttributeSpace
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.attributespace(v=AX.60)
ms:contentKeyID: 65316097
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.AttributeSpace
dev_langs:
- CSharp
- C++
- VB
---

# AttributeSpace Property

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Shared ReadOnly Property AttributeSpace As IDictionary(Of String, AttributeProductListing)
    Get
'Usage
Dim value As IDictionary(Of String, AttributeProductListing)

value = ChannelCatalogManager.AttributeSpace
```

``` csharp
public static IDictionary<string, AttributeProductListing> AttributeSpace { get; }
```

``` c++
public:
static property IDictionary<String^, AttributeProductListing^>^ AttributeSpace {
    IDictionary<String^, AttributeProductListing^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IDictionary](https://technet.microsoft.com/library/s4ys34ea\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [AttributeProductListing](attributeproductlisting-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)\>  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

