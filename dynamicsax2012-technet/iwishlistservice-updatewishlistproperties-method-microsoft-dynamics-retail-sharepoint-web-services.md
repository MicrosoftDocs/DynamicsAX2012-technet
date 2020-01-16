---
title: IWishListService.UpdateWishListProperties Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: UpdateWishListProperties Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.UpdateWishListProperties(System.String,System.String,System.Nullable{System.Boolean})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iwishlistservice.updatewishlistproperties(v=AX.60)
ms:contentKeyID: 62204862
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.UpdateWishListProperties
dev_langs:
- CSharp
- C++
- VB
---

# UpdateWishListProperties Method

Updates the wish list properties.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function UpdateWishListProperties ( _
    wishListId As String, _
    wishListName As String, _
    isFavorite As Nullable(Of Boolean) _
) As WishListResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim wishListName As String
Dim isFavorite As Nullable(Of Boolean)
Dim returnValue As WishListResponse

returnValue = instance.UpdateWishListProperties(wishListId, _
    wishListName, isFavorite)
```

``` csharp
[OperationContractAttribute]
WishListResponse UpdateWishListProperties(
    string wishListId,
    string wishListName,
    Nullable<bool> isFavorite
)
```

``` c++
[OperationContractAttribute]
WishListResponse^ UpdateWishListProperties(
    String^ wishListId, 
    String^ wishListName, 
    Nullable<bool> isFavorite
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - wishListName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isFavorite  
    Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))\>  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListResponse](wishlistresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish list.  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

