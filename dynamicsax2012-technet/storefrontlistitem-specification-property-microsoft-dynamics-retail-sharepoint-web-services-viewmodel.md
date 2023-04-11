---
title: StorefrontListItem.Specification Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Specification Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.Specification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.storefrontlistitem.specification(v=AX.60)
ms:contentKeyID: 62205709
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.StorefrontListItem.Specification
dev_langs:
- CSharp
- C++
- VB
---

# Specification Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the specification.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Specification As String
    Get
    Set
'Usage
Dim instance As StorefrontListItem
Dim value As String

value = instance.Specification

instance.Specification = value
```

``` csharp
[DataMemberAttribute]
public string Specification { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Specification {
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

