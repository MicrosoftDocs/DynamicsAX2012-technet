---
title: GetProductPartsDataServiceResponse.CategoryAssociations Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: CategoryAssociations Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.CategoryAssociations
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getproductpartsdataserviceresponse.categoryassociations(v=AX.60)
ms:contentKeyID: 65322962
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetProductPartsDataServiceResponse.CategoryAssociations
dev_langs:
- CSharp
- C++
- VB
---

# CategoryAssociations Property

Gets the product category associations.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property CategoryAssociations As ReadOnlyCollection(Of ProductCategoryAssociation)
    Get
    Private Set
'Usage
Dim instance As GetProductPartsDataServiceResponse
Dim value As ReadOnlyCollection(Of ProductCategoryAssociation)

value = instance.CategoryAssociations
```

``` csharp
public ReadOnlyCollection<ProductCategoryAssociation> CategoryAssociations { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<ProductCategoryAssociation^>^ CategoryAssociations {
    ReadOnlyCollection<ProductCategoryAssociation^>^ get ();
    private: void set (ReadOnlyCollection<ProductCategoryAssociation^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductCategoryAssociation](productcategoryassociation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetProductPartsDataServiceResponse Class](getproductpartsdataserviceresponse-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

