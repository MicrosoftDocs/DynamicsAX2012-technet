---
title: ProductSearchServiceRequest.QueryCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: QueryCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceRequest.QueryCriteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.productsearchservicerequest.querycriteria(v=AX.60)
ms:contentKeyID: 65321489
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.ProductSearchServiceRequest.QueryCriteria
dev_langs:
- CSharp
- C++
- VB
---

# QueryCriteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QueryCriteria As ProductSearchCriteria
    Get
    Private Set
'Usage
Dim instance As ProductSearchServiceRequest
Dim value As ProductSearchCriteria

value = instance.QueryCriteria
```

``` csharp
[DataMemberAttribute]
public ProductSearchCriteria QueryCriteria { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductSearchCriteria^ QueryCriteria {
    ProductSearchCriteria^ get ();
    private: void set (ProductSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[ProductSearchServiceRequest Class](productsearchservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

