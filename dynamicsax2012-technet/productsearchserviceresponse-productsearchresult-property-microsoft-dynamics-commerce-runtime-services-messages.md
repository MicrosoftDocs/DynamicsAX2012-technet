---
title: ProductSearchServiceResponse.ProductSearchResult Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ProductSearchResult Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceResponse.ProductSearchResult
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.productsearchserviceresponse.productsearchresult(v=AX.60)
ms:contentKeyID: 65317296
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceResponse.ProductSearchResult
dev_langs:
- CSharp
- C++
- VB
---

# ProductSearchResult Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductSearchResult As ProductSearchResult
    Get
    Private Set
'Usage
Dim instance As ProductSearchServiceResponse
Dim value As ProductSearchResult

value = instance.ProductSearchResult
```

``` csharp
[DataMemberAttribute]
public ProductSearchResult ProductSearchResult { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductSearchResult^ ProductSearchResult {
    ProductSearchResult^ get ();
    private: void set (ProductSearchResult^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductSearchServiceResponse Class](productsearchserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

