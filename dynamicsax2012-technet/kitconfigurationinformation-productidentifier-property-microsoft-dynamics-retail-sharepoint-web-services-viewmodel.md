---
title: KitConfigurationInformation.ProductIdentifier Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ProductIdentifier Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation.ProductIdentifier
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitconfigurationinformation.productidentifier(v=AX.60)
ms:contentKeyID: 62206530
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation.ProductIdentifier
dev_langs:
- CSharp
- C++
- VB
---

# ProductIdentifier Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates the product identifier of a specific kit configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ProductIdentifier As Long
    Get
    Set
'Usage
Dim instance As KitConfigurationInformation
Dim value As Long

value = instance.ProductIdentifier

instance.ProductIdentifier = value
```

``` csharp
[DataMemberAttribute]
public long ProductIdentifier { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property long long ProductIdentifier {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[KitConfigurationInformation Class](kitconfigurationinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

