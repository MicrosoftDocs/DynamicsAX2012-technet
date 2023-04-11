---
title: ProductSearchResponse.QueryResults Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: QueryResults Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ProductSearchResponse.QueryResults
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.productsearchresponse.queryresults(v=AX.60)
ms:contentKeyID: 62208882
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ProductSearchResponse.QueryResults
dev_langs:
- CSharp
- C++
- VB
---

# QueryResults Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the products that were inserted, updated or deleted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property QueryResults As ProductSearchResult
    Get
    Private Set
'Usage
Dim instance As ProductSearchResponse
Dim value As ProductSearchResult

value = instance.QueryResults
```

``` csharp
[DataMemberAttribute]
public ProductSearchResult QueryResults { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ProductSearchResult^ QueryResults {
    ProductSearchResult^ get ();
    private: void set (ProductSearchResult^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ProductSearchResponse Class](productsearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

