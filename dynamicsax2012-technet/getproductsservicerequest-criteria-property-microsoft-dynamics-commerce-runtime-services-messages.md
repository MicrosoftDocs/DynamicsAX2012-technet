---
title: GetProductsServiceRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductsservicerequest.criteria(v=AX.60)
ms:contentKeyID: 65322257
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductsServiceRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Criteria As ProductSearchCriteria
    Get
    Private Set
'Usage
Dim instance As GetProductsServiceRequest
Dim value As ProductSearchCriteria

value = instance.Criteria
```

``` csharp
public ProductSearchCriteria Criteria { get; private set; }
```

``` c++
public:
property ProductSearchCriteria^ Criteria {
    ProductSearchCriteria^ get ();
    private: void set (ProductSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetProductsServiceRequest Class](getproductsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

