---
title: IWishListService.DeleteWishList Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: DeleteWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.DeleteWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iwishlistservice.deletewishlist(v=AX.60)
ms:contentKeyID: 62205903
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.DeleteWishList
dev_langs:
- CSharp
- C++
- VB
---

# DeleteWishList Method

Deletes the wish list.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function DeleteWishList ( _
    wishListId As String _
) As NullResponse
'Usage
Dim instance As IWishListService
Dim wishListId As String
Dim returnValue As NullResponse

returnValue = instance.DeleteWishList(wishListId)
```

``` csharp
[OperationContractAttribute]
NullResponse DeleteWishList(
    string wishListId
)
```

``` c++
[OperationContractAttribute]
NullResponse^ DeleteWishList(
    String^ wishListId
)
```

#### Parameters

  - wishListId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [NullResponse](nullresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

