---
title: IShoppingCartService.RemoveItems Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services)
TOCTitle: RemoveItems Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.RemoveItems(System.Boolean,System.Collections.Generic.ICollection{System.String},Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.ishoppingcartservice.removeitems(v=AX.60)
ms:contentKeyID: 62203169
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.IShoppingCartService.RemoveItems
dev_langs:
- CSharp
- C++
- VB
---

# RemoveItems Method

Removes items from the shopping cart associated with the given identifier.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<OperationContractAttribute> _
Function RemoveItems ( _
    useSecureToken As Boolean, _
    lineIds As ICollection(Of String), _
    dataLevel As ShoppingCartDataLevel _
) As ShoppingCartResponse
'Usage
Dim instance As IShoppingCartService
Dim useSecureToken As Boolean
Dim lineIds As ICollection(Of String)
Dim dataLevel As ShoppingCartDataLevel
Dim returnValue As ShoppingCartResponse

returnValue = instance.RemoveItems(useSecureToken, _
    lineIds, dataLevel)
```

``` csharp
[OperationContractAttribute]
ShoppingCartResponse RemoveItems(
    bool useSecureToken,
    ICollection<string> lineIds,
    ShoppingCartDataLevel dataLevel
)
```

``` c++
[OperationContractAttribute]
ShoppingCartResponse^ RemoveItems(
    bool useSecureToken, 
    ICollection<String^>^ lineIds, 
    ShoppingCartDataLevel dataLevel
)
```

#### Parameters

  - useSecureToken  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - lineIds  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - dataLevel  
    Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartDataLevel](shoppingcartdatalevel-enumeration-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartResponse](shoppingcartresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
The service response containing the updated shopping cart.  

## See Also

#### Reference

[IShoppingCartService Interface](ishoppingcartservice-interface-microsoft-dynamics-retail-sharepoint-web-services.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services Namespace](microsoft-dynamics-retail-sharepoint-web-services-namespace.md)

