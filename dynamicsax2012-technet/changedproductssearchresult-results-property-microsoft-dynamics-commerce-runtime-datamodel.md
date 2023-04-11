---
title: ChangedProductsSearchResult.Results Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Results Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult.Results
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.changedproductssearchresult.results(v=AX.60)
ms:contentKeyID: 62207643
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangedProductsSearchResult.Results
dev_langs:
- CSharp
- C++
- VB
---

# Results Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the results associated with this query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Results As ReadOnlyCollection(Of Product)
    Get
    Set
'Usage
Dim instance As ChangedProductsSearchResult
Dim value As ReadOnlyCollection(Of Product)

value = instance.Results

instance.Results = value
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<Product> Results { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<Product^>^ Results {
    ReadOnlyCollection<Product^>^ get ();
    void set (ReadOnlyCollection<Product^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Product](product-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The set of changed products.  

## See Also

#### Reference

[ChangedProductsSearchResult Class](changedproductssearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

