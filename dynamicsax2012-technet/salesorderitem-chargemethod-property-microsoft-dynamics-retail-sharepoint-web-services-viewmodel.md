---
title: SalesOrderItem.ChargeMethod Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ChargeMethod Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem.ChargeMethod
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.salesorderitem.chargemethod(v=AX.60)
ms:contentKeyID: 62207341
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.SalesOrderItem.ChargeMethod
dev_langs:
- CSharp
- C++
- VB
---

# ChargeMethod Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the method for computing this charge line.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChargeMethod As String
    Get
    Set
'Usage
Dim instance As SalesOrderItem
Dim value As String

value = instance.ChargeMethod

instance.ChargeMethod = value
```

``` csharp
[DataMemberAttribute]
public string ChargeMethod { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ChargeMethod {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Charge computation methods include: fixed, percent, pieces, and external charges.

## See Also

#### Reference

[SalesOrderItem Class](salesorderitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

