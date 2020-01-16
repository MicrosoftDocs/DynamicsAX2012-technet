---
title: KitConfigurationInformation.Title Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: Title Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation.Title
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitconfigurationinformation.title(v=AX.60)
ms:contentKeyID: 62204433
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation.Title
dev_langs:
- CSharp
- C++
- VB
---

# Title Property

Indicates the title of a specific kit configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Title As String
    Get
    Set
'Usage
Dim instance As KitConfigurationInformation
Dim value As String

value = instance.Title

instance.Title = value
```

``` csharp
[DataMemberAttribute]
public string Title { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Title {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[KitConfigurationInformation Class](kitconfigurationinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

