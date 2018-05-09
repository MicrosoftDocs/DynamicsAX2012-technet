---
title: GetProductRefinersDataRequest.SearchCriteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SearchCriteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataRequest.SearchCriteria
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductrefinersdatarequest.searchcriteria(v=AX.60)
ms:contentKeyID: 65321826
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductRefinersDataRequest.SearchCriteria
dev_langs:
- CSharp
- C++
- VB
---

# SearchCriteria Property

Gets the product search criteria to be used to retrieve refiners.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property SearchCriteria As ProductSearchCriteria
    Get
    Private Set
'Usage
Dim instance As GetProductRefinersDataRequest
Dim value As ProductSearchCriteria

value = instance.SearchCriteria
```

``` csharp
public ProductSearchCriteria SearchCriteria { get; private set; }
```

``` c++
public:
property ProductSearchCriteria^ SearchCriteria {
    ProductSearchCriteria^ get ();
    private: void set (ProductSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetProductRefinersDataRequest Class](getproductrefinersdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

