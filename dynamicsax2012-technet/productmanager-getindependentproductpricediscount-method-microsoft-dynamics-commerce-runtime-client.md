---
title: ProductManager.GetIndependentProductPriceDiscount Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetIndependentProductPriceDiscount Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetIndependentProductPriceDiscount(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain,System.Collections.Generic.IEnumerable{System.Int64},System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.AffiliationLoyaltyTier})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getindependentproductpricediscount(v=AX.60)
ms:contentKeyID: 65323191
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetIndependentProductPriceDiscount
dev_langs:
- CSharp
- C++
- VB
---

# GetIndependentProductPriceDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetIndependentProductPriceDiscount ( _
    context As ProjectionDomain, _
    productIds As IEnumerable(Of Long), _
    customerAccountNumber As String, _
    affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier) _
) As ReadOnlyCollection(Of ProductPrice)
'Usage
Dim instance As ProductManager
Dim context As ProjectionDomain
Dim productIds As IEnumerable(Of Long)
Dim customerAccountNumber As String
Dim affiliationLoyaltyTiers As IEnumerable(Of AffiliationLoyaltyTier)
Dim returnValue As ReadOnlyCollection(Of ProductPrice)

returnValue = instance.GetIndependentProductPriceDiscount(context, _
    productIds, customerAccountNumber, _
    affiliationLoyaltyTiers)
```

``` csharp
public ReadOnlyCollection<ProductPrice> GetIndependentProductPriceDiscount(
    ProjectionDomain context,
    IEnumerable<long> productIds,
    string customerAccountNumber,
    IEnumerable<AffiliationLoyaltyTier> affiliationLoyaltyTiers
)
```

``` c++
public:
ReadOnlyCollection<ProductPrice^>^ GetIndependentProductPriceDiscount(
    ProjectionDomain^ context, 
    IEnumerable<long long>^ productIds, 
    String^ customerAccountNumber, 
    IEnumerable<AffiliationLoyaltyTier^>^ affiliationLoyaltyTiers
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - affiliationLoyaltyTiers  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[AffiliationLoyaltyTier](affiliationloyaltytier-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ProductPrice](productprice-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

