---
title: StorefrontListItem.CustomerItemNumber Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: CustomerItemNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.CustomerItemNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storefrontlistitem.customeritemnumber(v=AX.60)
ms:contentKeyID: 62204099
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.CustomerItemNumber
dev_langs:
- CSharp
- C++
- VB
---

# CustomerItemNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer item number.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CustomerItemNumber As String
    Get
    Set
'Usage
Dim instance As StorefrontListItem
Dim value As String

value = instance.CustomerItemNumber

instance.CustomerItemNumber = value
```

``` csharp
[DataMemberAttribute]
public string CustomerItemNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CustomerItemNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StorefrontListItem Class](storefrontlistitem-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

