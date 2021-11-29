---
title: IWishListService.DeleteWishList Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services)
TOCTitle: DeleteWishList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.DeleteWishList(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.services.iwishlistservice.deletewishlist(v=AX.60)
ms:contentKeyID: 65316315
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.IWishListService.DeleteWishList
dev_langs:
- CSharp
- C++
- VB
---

# DeleteWishList Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.dll)

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

Type: [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services.NullResponse](nullresponse-class-microsoft-dynamics-retail-ecommerce-sdk-services.md)  

## See Also

#### Reference

[IWishListService Interface](iwishlistservice-interface-microsoft-dynamics-retail-ecommerce-sdk-services.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Services Namespace](microsoft-dynamics-retail-ecommerce-sdk-services-namespace.md)

