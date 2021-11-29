---
title: KitConfigurationResponse.KitConfigurationInformation Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: KitConfigurationInformation Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationResponse.KitConfigurationInformation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitconfigurationresponse.kitconfigurationinformation(v=AX.60)
ms:contentKeyID: 62203290
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationResponse.KitConfigurationInformation
dev_langs:
- CSharp
- C++
- VB
---

# KitConfigurationInformation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or set the information for a specific kit configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property KitConfigurationInformation As KitConfigurationInformation
    Get
    Set
'Usage
Dim instance As KitConfigurationResponse
Dim value As KitConfigurationInformation

value = instance.KitConfigurationInformation

instance.KitConfigurationInformation = value
```

``` csharp
[DataMemberAttribute]
public KitConfigurationInformation KitConfigurationInformation { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property KitConfigurationInformation^ KitConfigurationInformation {
    KitConfigurationInformation^ get ();
    void set (KitConfigurationInformation^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation](kitconfigurationinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)  
Returns [KitConfigurationInformation](kitconfigurationinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md).  

## See Also

#### Reference

[KitConfigurationResponse Class](kitconfigurationresponse-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

