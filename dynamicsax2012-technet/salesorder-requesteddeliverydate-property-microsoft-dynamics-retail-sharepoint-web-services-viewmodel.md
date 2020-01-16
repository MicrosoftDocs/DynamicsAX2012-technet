---
title: SalesOrder.RequestedDeliveryDate Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: RequestedDeliveryDate Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.RequestedDeliveryDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorder.requesteddeliverydate(v=AX.60)
ms:contentKeyID: 62207540
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrder.RequestedDeliveryDate
dev_langs:
- CSharp
- C++
- VB
---

# RequestedDeliveryDate Property

Gets or sets the requested delivery date.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RequestedDeliveryDate As String
    Get
    Set
'Usage
Dim instance As SalesOrder
Dim value As String

value = instance.RequestedDeliveryDate

instance.RequestedDeliveryDate = value
```

``` csharp
[DataMemberAttribute]
public string RequestedDeliveryDate { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ RequestedDeliveryDate {
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

