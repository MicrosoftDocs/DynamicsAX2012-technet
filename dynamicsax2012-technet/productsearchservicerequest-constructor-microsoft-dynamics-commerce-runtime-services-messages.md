---
title: ProductSearchServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ProductSearchServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.productsearchservicerequest.productsearchservicerequest(v=AX.60)
ms:contentKeyID: 65320768
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# ProductSearchServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    productSearchCriteria As ProductSearchCriteria, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim productSearchCriteria As ProductSearchCriteria
Dim queryResultSettings As QueryResultSettings

Dim instance As New ProductSearchServiceRequest(productSearchCriteria, _
    queryResultSettings)
```

``` csharp
public ProductSearchServiceRequest(
    ProductSearchCriteria productSearchCriteria,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
ProductSearchServiceRequest(
    ProductSearchCriteria^ productSearchCriteria, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - productSearchCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductSearchServiceRequest Class](productsearchservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

