---
title: SalesOrder.OrderPlacedDate Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: OrderPlacedDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.OrderPlacedDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorder.orderplaceddate(v=AX.60)
ms:contentKeyID: 62204697
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.OrderPlacedDate
dev_langs:
- CSharp
- C++
- VB
---

# OrderPlacedDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the order placed date.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderPlacedDate As String
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As String

value = instance.OrderPlacedDate

instance.OrderPlacedDate = value
```

``` csharp
[DataMemberAttribute]
public string OrderPlacedDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OrderPlacedDate {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesOrder Class](salesorder-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

