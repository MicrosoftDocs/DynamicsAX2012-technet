---
title: ShoppingCartController.CommenceCheckout Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: CommenceCheckout Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ShoppingCartController.CommenceCheckout(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.shoppingcartcontroller.commencecheckout(v=AX.60)
ms:contentKeyID: 62206187
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.ShoppingCartController.CommenceCheckout
dev_langs:
- CSharp
- C++
- VB
---

# CommenceCheckout Method

Starts the checkout process by creating a secure cart and returning it.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function CommenceCheckout ( _
    shoppingCartId As String, _
    secureCartIdToReplace As String _
) As ShoppingCart
'Usage
Dim shoppingCartId As String
Dim secureCartIdToReplace As String
Dim returnValue As ShoppingCart

returnValue = ShoppingCartController.CommenceCheckout(shoppingCartId, _
    secureCartIdToReplace)
```

``` csharp
public static ShoppingCart CommenceCheckout(
    string shoppingCartId,
    string secureCartIdToReplace
)
```

``` c++
public:
static ShoppingCart^ CommenceCheckout(
    String^ shoppingCartId, 
    String^ secureCartIdToReplace
)
```

#### Parameters

  - shoppingCartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - secureCartIdToReplace  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCart](shoppingcart-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
A new cart with a random cart ID that should be used during the secure checkout process.  

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
<td><a href="https://technet.microsoft.com/en-us/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Thrown when shoppingCartId is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ShoppingCartController Class](shoppingcartcontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

