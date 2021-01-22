---
title: ChannelCatalogManager.CreateCatalogManager Method  (Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement)
TOCTitle: CreateCatalogManager Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.CreateCatalogManager(System.Int64,System.String,System.Boolean,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Category})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sp.publishing.connector.catalogmanagement.channelcatalogmanager.createcatalogmanager(v=AX.60)
ms:contentKeyID: 65316037
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager.CreateCatalogManager
dev_langs:
- CSharp
- C++
- VB
---

# CreateCatalogManager Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector (in Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CreateCatalogManager ( _
    channelId As Long, _
    connectionString As String, _
    isInitialPublishing As Boolean, _
    attributeSpace As IEnumerable(Of AttributeProduct), _
    channelCategories As IEnumerable(Of Category) _
) As ChannelCatalogManager
'Usage
Dim channelId As Long
Dim connectionString As String
Dim isInitialPublishing As Boolean
Dim attributeSpace As IEnumerable(Of AttributeProduct)
Dim channelCategories As IEnumerable(Of Category)
Dim returnValue As ChannelCatalogManager

returnValue = ChannelCatalogManager.CreateCatalogManager(channelId, _
    connectionString, isInitialPublishing, _
    attributeSpace, channelCategories)
```

``` csharp
public static ChannelCatalogManager CreateCatalogManager(
    long channelId,
    string connectionString,
    bool isInitialPublishing,
    IEnumerable<AttributeProduct> attributeSpace,
    IEnumerable<Category> channelCategories
)
```

``` c++
public:
static ChannelCatalogManager^ CreateCatalogManager(
    long long channelId, 
    String^ connectionString, 
    bool isInitialPublishing, 
    IEnumerable<AttributeProduct^>^ attributeSpace, 
    IEnumerable<Category^>^ channelCategories
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - connectionString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isInitialPublishing  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - attributeSpace  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<AttributeProduct\>  

<!-- end list -->

  - channelCategories  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<Category\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement.ChannelCatalogManager](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)  

## See Also

#### Reference

[ChannelCatalogManager Class](channelcatalogmanager-class-microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement.md)

[Microsoft.Dynamics.Retail.Ecommerce.SP.Publishing.Connector.CatalogManagement Namespace](microsoft-dynamics-retail-ecommerce-sp-publishing-connector-catalogmanagement-namespace.md)

