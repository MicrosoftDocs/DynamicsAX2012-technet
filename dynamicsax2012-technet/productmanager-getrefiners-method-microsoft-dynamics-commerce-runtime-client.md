---
title: ProductManager.GetRefiners Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetRefiners Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetRefiners(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.client.productmanager.getrefiners(v=AX.60)
ms:contentKeyID: 65323130
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetRefiners
dev_langs:
- CSharp
- C++
- VB
---

# GetRefiners Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetRefiners ( _
    searchCriteria As ProductSearchCriteria _
) As ReadOnlyCollection(Of ProductRefiner)
'Usage
Dim instance As ProductManager
Dim searchCriteria As ProductSearchCriteria
Dim returnValue As ReadOnlyCollection(Of ProductRefiner)

returnValue = instance.GetRefiners(searchCriteria)
```

``` csharp
public ReadOnlyCollection<ProductRefiner> GetRefiners(
    ProductSearchCriteria searchCriteria
)
```

``` c++
public:
ReadOnlyCollection<ProductRefiner^>^ GetRefiners(
    ProductSearchCriteria^ searchCriteria
)
```

#### Parameters

  - searchCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ProductRefiner](productrefiner-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

