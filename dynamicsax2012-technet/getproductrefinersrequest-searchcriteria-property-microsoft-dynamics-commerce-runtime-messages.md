---
title: GetProductRefinersRequest.SearchCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SearchCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductRefinersRequest.SearchCriteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getproductrefinersrequest.searchcriteria(v=AX.60)
ms:contentKeyID: 65321553
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductRefinersRequest.SearchCriteria
dev_langs:
- CSharp
- C++
- VB
---

# SearchCriteria Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property SearchCriteria As ProductSearchCriteria
    Get
    Set
'Usage
Dim instance As GetProductRefinersRequest
Dim value As ProductSearchCriteria

value = instance.SearchCriteria

instance.SearchCriteria = value
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public ProductSearchCriteria SearchCriteria { get; set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property ProductSearchCriteria^ SearchCriteria {
    ProductSearchCriteria^ get ();
    void set (ProductSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetProductRefinersRequest Class](getproductrefinersrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

