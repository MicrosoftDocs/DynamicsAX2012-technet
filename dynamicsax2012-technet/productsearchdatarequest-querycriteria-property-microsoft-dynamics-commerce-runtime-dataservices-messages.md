---
title: ProductSearchDataRequest.QueryCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: QueryCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataRequest.QueryCriteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.productsearchdatarequest.querycriteria(v=AX.60)
ms:contentKeyID: 65322917
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ProductSearchDataRequest.QueryCriteria
dev_langs:
- CSharp
- C++
- VB
---

# QueryCriteria Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the product search criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QueryCriteria As ProductSearchCriteria
    Get
    Private Set
'Usage
Dim instance As ProductSearchDataRequest
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
Returns [ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductSearchDataRequest Class](productsearchdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

