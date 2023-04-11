---
title: LoyaltyController.UpdateLoyaltyCardId Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: UpdateLoyaltyCardId Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.UpdateLoyaltyCardId(System.String,System.String,Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.loyaltycontroller.updateloyaltycardid(v=AX.60)
ms:contentKeyID: 62204491
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.UpdateLoyaltyCardId
dev_langs:
- CSharp
- C++
- VB
---

# UpdateLoyaltyCardId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates the loyalty card ID.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function UpdateLoyaltyCardId ( _
    shoppingCartId As String, _
    loyaltyCardId As String, _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCart
'Usage
Dim shoppingCartId As String
Dim loyaltyCardId As String
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCart

returnValue = LoyaltyController.UpdateLoyaltyCardId(shoppingCartId, _
    loyaltyCardId, dataLevel)
```

``` csharp
public static ShoppingCart UpdateLoyaltyCardId(
    string shoppingCartId,
    string loyaltyCardId,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
public:
static ShoppingCart^ UpdateLoyaltyCardId(
    String^ shoppingCartId, 
    String^ loyaltyCardId, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A shopping cart.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Thrown when shoppingCartId is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

