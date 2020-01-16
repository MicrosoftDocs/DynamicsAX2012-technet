---
title: BeginReadChangedProductsRequest.SearchCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SearchCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsRequest.SearchCriteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.beginreadchangedproductsrequest.searchcriteria(v=AX.60)
ms:contentKeyID: 62214525
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.BeginReadChangedProductsRequest.SearchCriteria
dev_langs:
- CSharp
- C++
- VB
---

# SearchCriteria Property

Gets or sets search criteria.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property SearchCriteria As ChangedProductsSearchCriteria
    Get
    Set
'Usage
Dim instance As BeginReadChangedProductsRequest
Dim value As ChangedProductsSearchCriteria

value = instance.SearchCriteria

instance.SearchCriteria = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public ChangedProductsSearchCriteria SearchCriteria { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property ChangedProductsSearchCriteria^ SearchCriteria {
    ChangedProductsSearchCriteria^ get ();
    void set (ChangedProductsSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChangedProductsSearchCriteria](changedproductssearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[BeginReadChangedProductsRequest Class](beginreadchangedproductsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

