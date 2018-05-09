---
title: ShoppingCartItem Class (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ShoppingCartItem Class
ms:assetid: T:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.shoppingcartitem(v=AX.60)
ms:contentKeyID: 62201949
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem
dev_langs:
- CSharp
- C++
- VB
---

# ShoppingCartItem Class

The shopping cart item view model representation.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<SerializableAttribute> _
<DataContractAttribute> _
Public NotInheritable Class ShoppingCartItem _
    Inherits TransactionItem
'Usage
Dim instance As ShoppingCartItem
```

``` csharp
[SerializableAttribute]
[DataContractAttribute]
public sealed class ShoppingCartItem : TransactionItem
```

``` c++
[SerializableAttribute]
[DataContractAttribute]
public ref class ShoppingCartItem sealed : public TransactionItem
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.TransactionItem](transactionitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
    Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.ShoppingCartItem  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

