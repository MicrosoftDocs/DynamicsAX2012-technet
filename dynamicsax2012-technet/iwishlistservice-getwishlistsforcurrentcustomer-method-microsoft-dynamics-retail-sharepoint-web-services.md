---
title: IWishListService.GetWishListsForCurrentCustomer Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: GetWishListsForCurrentCustomer Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.GetWishListsForCurrentCustomer
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.iwishlistservice.getwishlistsforcurrentcustomer(v=AX.60)
ms:contentKeyID: 62203834
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IWishListService.GetWishListsForCurrentCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetWishListsForCurrentCustomer Method

Get the wish lists corresponding to customer.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function GetWishListsForCurrentCustomer As WishListCollectionResponse
'Usage
Dim instance As IWishListService
Dim returnValue As WishListCollectionResponse

returnValue = instance.GetWishListsForCurrentCustomer()
```

``` csharp
[OperationContractAttribute]
WishListCollectionResponse GetWishListsForCurrentCustomer()
```

``` c++
[OperationContractAttribute]
WishListCollectionResponse^ GetWishListsForCurrentCustomer()
```

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.WishListCollectionResponse](wishlistcollectionresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the wish lists.  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

