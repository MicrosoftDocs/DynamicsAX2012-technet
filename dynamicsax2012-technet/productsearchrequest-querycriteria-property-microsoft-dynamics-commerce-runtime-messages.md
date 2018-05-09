---
title: ProductSearchRequest.QueryCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: QueryCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.ProductSearchRequest.QueryCriteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.productsearchrequest.querycriteria(v=AX.60)
ms:contentKeyID: 62207836
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.ProductSearchRequest.QueryCriteria
dev_langs:
- CSharp
- C++
- VB
---

# QueryCriteria Property

Gets or sets the search criteria for this query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property QueryCriteria As ProductSearchCriteria
    Get
    Set
'Usage
Dim instance As ProductSearchRequest
Dim value As ProductSearchCriteria

value = instance.QueryCriteria

instance.QueryCriteria = value
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public ProductSearchCriteria QueryCriteria { get; set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property ProductSearchCriteria^ QueryCriteria {
    ProductSearchCriteria^ get ();
    void set (ProductSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The search criteria for this query.  

## See Also

#### Reference

[ProductSearchRequest Class](productsearchrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

