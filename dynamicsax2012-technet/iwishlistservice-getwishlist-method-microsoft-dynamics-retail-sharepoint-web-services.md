---
title: IWishListService.GetWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.GetWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iwishlistservice.getwishlist(v=AX.60)
ms:contentKeyID: 62206987
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.GetWishList
dev_langs:
- CSharp
- C++
- VB
---

# GetWishList Method

Get the wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetWishList ( _
    wishListId As String _
) As WishListResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim returnValue As WishListResponse

returnValue = instance.GetWishList(wishListId)
```

``` csharp
[OperationContractAttribute]
WishListResponse GetWishList(
    string wishListId
)
```

``` c++
[OperationContractAttribute]
WishListResponse^ GetWishList(
    String^ wishListId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish list.  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

