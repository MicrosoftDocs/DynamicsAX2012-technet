---
title: SalesOrderResponse.SalesOrder Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorderresponse.salesorder(v=AX.60)
ms:contentKeyID: 62203177
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderResponse.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sales order.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrder As SalesOrder
    Get
    Set
'Usage
Dim instance As SalesOrderResponse
Dim value As SalesOrder

value = instance.SalesOrder

instance.SalesOrder = value
```

``` csharp
[DataMemberAttribute]
public SalesOrder SalesOrder { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ SalesOrder {
    SalesOrder^ get ();
    void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[SalesOrderResponse Class](salesorderresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

