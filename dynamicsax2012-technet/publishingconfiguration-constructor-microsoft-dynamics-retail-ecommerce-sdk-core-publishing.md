---
title: PublishingConfiguration Constructor  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing)
TOCTitle: PublishingConfiguration Constructor
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingConfiguration.#ctor(System.Int32,System.Int32,System.Boolean,System.Int32,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.publishing.publishingconfiguration.publishingconfiguration(v=AX.60)
ms:contentKeyID: 65316877
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing.PublishingConfiguration.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PublishingConfiguration Constructor

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    categoriesPageSize As Integer, _
    productAttributesPageSize As Integer, _
    forceNoCatalogPublishing As Boolean, _
    crtListingPageSize As Integer, _
    forceTimingInfoLogging As Boolean, _
    checkEveryListingForRemoval As Boolean _
)
'Usage
Dim categoriesPageSize As Integer
Dim productAttributesPageSize As Integer
Dim forceNoCatalogPublishing As Boolean
Dim crtListingPageSize As Integer
Dim forceTimingInfoLogging As Boolean
Dim checkEveryListingForRemoval As Boolean

Dim instance As New PublishingConfiguration(categoriesPageSize, _
    productAttributesPageSize, forceNoCatalogPublishing, _
    crtListingPageSize, forceTimingInfoLogging, _
    checkEveryListingForRemoval)
```

``` csharp
public PublishingConfiguration(
    int categoriesPageSize,
    int productAttributesPageSize,
    bool forceNoCatalogPublishing,
    int crtListingPageSize,
    bool forceTimingInfoLogging,
    bool checkEveryListingForRemoval
)
```

``` c++
public:
PublishingConfiguration(
    int categoriesPageSize, 
    int productAttributesPageSize, 
    bool forceNoCatalogPublishing, 
    int crtListingPageSize, 
    bool forceTimingInfoLogging, 
    bool checkEveryListingForRemoval
)
```

#### Parameters

  - categoriesPageSize  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - productAttributesPageSize  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - forceNoCatalogPublishing  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - crtListingPageSize  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - forceTimingInfoLogging  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - checkEveryListingForRemoval  
    Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[PublishingConfiguration Class](publishingconfiguration-class-microsoft-dynamics-retail-ecommerce-sdk-core-publishing.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Publishing Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-publishing-namespace.md)

