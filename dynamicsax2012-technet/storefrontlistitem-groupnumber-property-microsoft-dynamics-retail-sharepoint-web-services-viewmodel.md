---
title: StorefrontListItem.GroupNumber Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: GroupNumber Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.GroupNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storefrontlistitem.groupnumber(v=AX.60)
ms:contentKeyID: 62206450
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.GroupNumber
dev_langs:
- CSharp
- C++
- VB
---

# GroupNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the group number.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GroupNumber As String
    Get
    Set
'Usage
Dim instance As StorefrontListItem
Dim value As String

value = instance.GroupNumber

instance.GroupNumber = value
```

``` csharp
[DataMemberAttribute]
public string GroupNumber { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ GroupNumber {
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

