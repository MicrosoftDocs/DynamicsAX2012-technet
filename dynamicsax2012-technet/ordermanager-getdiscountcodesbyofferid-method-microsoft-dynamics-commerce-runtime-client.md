---
title: OrderManager.GetDiscountCodesByOfferId Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetDiscountCodesByOfferId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodesByOfferId(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.ordermanager.getdiscountcodesbyofferid(v=AX.60)
ms:contentKeyID: 65322647
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.OrderManager.GetDiscountCodesByOfferId
dev_langs:
- CSharp
- C++
- VB
---

# GetDiscountCodesByOfferId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetDiscountCodesByOfferId ( _
    offerId As String, _
    settings As QueryResultSettings _
) As PagedResult(Of DiscountCode)
'Usage
Dim instance As OrderManager
Dim offerId As String
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of DiscountCode)

returnValue = instance.GetDiscountCodesByOfferId(offerId, _
    settings)
```

``` csharp
public PagedResult<DiscountCode> GetDiscountCodesByOfferId(
    string offerId,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<DiscountCode^>^ GetDiscountCodesByOfferId(
    String^ offerId, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - offerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[OrderManager Class](ordermanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

