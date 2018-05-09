---
title: ProductDataManager.GetLinkedProducts Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLinkedProducts Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetLinkedProducts(System.Collections.Generic.IEnumerable{System.Int64})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.productdatamanager.getlinkedproducts(v=AX.60)
ms:contentKeyID: 62211537
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductDataManager.GetLinkedProducts
dev_langs:
- CSharp
- C++
- VB
---

# GetLinkedProducts Method

Given a set of product identifiers, return all linked products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetLinkedProducts ( _
    productIds As IEnumerable(Of Long) _
) As ReadOnlyCollection(Of LinkedProduct)
'Usage
Dim instance As ProductDataManager
Dim productIds As IEnumerable(Of Long)
Dim returnValue As ReadOnlyCollection(Of LinkedProduct)

returnValue = instance.GetLinkedProducts(productIds)
```

``` csharp
public ReadOnlyCollection<LinkedProduct> GetLinkedProducts(
    IEnumerable<long> productIds
)
```

``` c++
public:
virtual ReadOnlyCollection<LinkedProduct^>^ GetLinkedProducts(
    IEnumerable<long long>^ productIds
) sealed
```

#### Parameters

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Products linked to the given Ids, otherwise empty.  

#### Implements

[IProductDataManager.GetLinkedProducts(IEnumerable\<Int64\>)](iproductdatamanager-getlinkedproducts-method-microsoft-dynamics-commerce-runtime-data.md)  

## See Also

#### Reference

[ProductDataManager Class](productdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

