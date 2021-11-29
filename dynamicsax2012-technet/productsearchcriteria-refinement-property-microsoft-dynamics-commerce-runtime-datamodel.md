---
title: ProductSearchCriteria.Refinement Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Refinement Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Refinement
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.refinement(v=AX.60)
ms:contentKeyID: 62210128
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Refinement
dev_langs:
- CSharp
- C++
- VB
---

# Refinement Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the refinements by which to search for products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Refinement As IList(Of ProductRefinerValue)
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As IList(Of ProductRefinerValue)

value = instance.Refinement

instance.Refinement = value
```

``` csharp
[DataMemberAttribute]
public IList<ProductRefinerValue> Refinement { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<ProductRefinerValue^>^ Refinement {
    IList<ProductRefinerValue^>^ get ();
    void set (IList<ProductRefinerValue^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[ProductRefinerValue](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

