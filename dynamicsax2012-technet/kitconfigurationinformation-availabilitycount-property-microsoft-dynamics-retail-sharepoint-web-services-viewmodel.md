---
title: KitConfigurationInformation.AvailabilityCount Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: AvailabilityCount Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation.AvailabilityCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.kitconfigurationinformation.availabilitycount(v=AX.60)
ms:contentKeyID: 62206363
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.KitConfigurationInformation.AvailabilityCount
dev_langs:
- CSharp
- C++
- VB
---

# AvailabilityCount Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indiciates the number of units available for a specific kit configuration.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AvailabilityCount As Decimal
    Get
    Set
'Usage
Dim instance As KitConfigurationInformation
Dim value As Decimal

value = instance.AvailabilityCount

instance.AvailabilityCount = value
```

``` csharp
[DataMemberAttribute]
public decimal AvailabilityCount { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal AvailabilityCount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[KitConfigurationInformation Class](kitconfigurationinformation-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

