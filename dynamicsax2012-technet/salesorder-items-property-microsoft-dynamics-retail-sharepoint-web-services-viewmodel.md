---
title: SalesOrder.Items Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.Items
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorder.items(v=AX.60)
ms:contentKeyID: 62206008
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the items ordered.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As Collection(Of SalesOrderItem)
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As Collection(Of SalesOrderItem)

value = instance.Items

instance.Items = value
```

``` csharp
[DataMemberAttribute]
public Collection<SalesOrderItem> Items { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Collection<SalesOrderItem^>^ Items {
    Collection<SalesOrderItem^>^ get ();
    void set (Collection<SalesOrderItem^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[SalesOrderItem](salesorderitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

