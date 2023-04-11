---
title: StoreProductAvailability.SelectDisabled Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: SelectDisabled Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailability.SelectDisabled
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storeproductavailability.selectdisabled(v=AX.60)
ms:contentKeyID: 62206383
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StoreProductAvailability.SelectDisabled
dev_langs:
- CSharp
- C++
- VB
---

# SelectDisabled Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the flag allowing store selection.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SelectDisabled As String
    Get
    Set
'Usage
Dim instance As StoreProductAvailability
Dim value As String

value = instance.SelectDisabled

instance.SelectDisabled = value
```

``` csharp
[DataMemberAttribute]
public string SelectDisabled { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ SelectDisabled {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StoreProductAvailability Class](storeproductavailability-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

