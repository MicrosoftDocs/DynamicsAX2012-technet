---
title: SalesOrder Constructor (Collection(SalesOrderItem)) (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SalesOrder Constructor (Collection(SalesOrderItem))
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.#ctor(System.Collections.ObjectModel.Collection{Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorder.salesorder(v=AX.60)
ms:contentKeyID: 62204873
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SalesOrder Constructor (Collection(SalesOrderItem))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [SalesOrder](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md) class with the specified sales order items.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    items As Collection(Of SalesOrderItem) _
)
'Usage
Dim items As Collection(Of SalesOrderItem)

Dim instance As New SalesOrder(items)
```

``` csharp
public SalesOrder(
    Collection<SalesOrderItem> items
)
```

``` c++
public:
SalesOrder(
    Collection<SalesOrderItem^>^ items
)
```

#### Parameters

  - items  
    Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[SalesOrderItem](salesorderitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[SalesOrder Overload](salesorder-constructor-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

