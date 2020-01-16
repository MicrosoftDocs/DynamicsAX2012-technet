---
title: GetProductPartsDataServiceRequest.Criteria Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Criteria Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.Criteria
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataservicerequest.criteria(v=AX.60)
ms:contentKeyID: 65318828
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceRequest.Criteria
dev_langs:
- CSharp
- C++
- VB
---

# Criteria Property

Gets the product search criteria for the result set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property Criteria As ProductSearchCriteria
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceRequest
Dim value As ProductSearchCriteria

value = instance.Criteria
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public ProductSearchCriteria Criteria { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property ProductSearchCriteria^ Criteria {
    ProductSearchCriteria^ get ();
    private: void set (ProductSearchCriteria^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetProductPartsDataServiceRequest Class](getproductpartsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

