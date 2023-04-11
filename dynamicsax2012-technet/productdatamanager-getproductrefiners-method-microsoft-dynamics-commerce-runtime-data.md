---
title: ProductDataManager.GetProductRefiners Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetProductRefiners Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductRefiners(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria,System.String,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefiner}@,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRefinerValue}@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getproductrefiners(v=AX.60)
ms:contentKeyID: 65320280
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetProductRefiners
dev_langs:
- CSharp
- C++
- VB
---

# GetProductRefiners Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub GetProductRefiners ( _
    searchCriteria As ProductSearchCriteria, _
    locale As String, _
    <OutAttribute> ByRef refiners As ReadOnlyCollection(Of ProductRefiner), _
    <OutAttribute> ByRef refinerValues As ReadOnlyCollection(Of ProductRefinerValue) _
)
'Usage
Dim instance As ProductDataManager
Dim searchCriteria As ProductSearchCriteria
Dim locale As String
Dim refiners As ReadOnlyCollection(Of ProductRefiner)
Dim refinerValues As ReadOnlyCollection(Of ProductRefinerValue)

instance.GetProductRefiners(searchCriteria, _
    locale, refiners, refinerValues)
```

``` csharp
public void GetProductRefiners(
    ProductSearchCriteria searchCriteria,
    string locale,
    out ReadOnlyCollection<ProductRefiner> refiners,
    out ReadOnlyCollection<ProductRefinerValue> refinerValues
)
```

``` c++
public:
void GetProductRefiners(
    ProductSearchCriteria^ searchCriteria, 
    String^ locale, 
    [OutAttribute] ReadOnlyCollection<ProductRefiner^>^% refiners, 
    [OutAttribute] ReadOnlyCollection<ProductRefinerValue^>^% refinerValues
)
```

#### Parameters

  - searchCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - locale  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - refiners  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRefiner](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - refinerValues  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductRefinerValue](productrefinervalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

