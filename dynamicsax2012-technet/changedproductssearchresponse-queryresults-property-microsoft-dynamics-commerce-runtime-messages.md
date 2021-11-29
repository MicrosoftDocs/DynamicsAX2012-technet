---
title: ChangedProductsSearchResponse.QueryResults Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: QueryResults Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ChangedProductsSearchResponse.QueryResults
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.changedproductssearchresponse.queryresults(v=AX.60)
ms:contentKeyID: 62208863
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ChangedProductsSearchResponse.QueryResults
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
Public Property QueryResults As ChangedProductsSearchResult
    Get
    Private Set
'Usage
Dim instance As ChangedProductsSearchResponse
Dim value As ChangedProductsSearchResult

value = instance.QueryResults
```

``` csharp
[DataMemberAttribute]
public ChangedProductsSearchResult QueryResults { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ChangedProductsSearchResult^ QueryResults {
    ChangedProductsSearchResult^ get ();
    private: void set (ChangedProductsSearchResult^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChangedProductsSearchResult](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChangedProductsSearchResponse Class](changedproductssearchresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

