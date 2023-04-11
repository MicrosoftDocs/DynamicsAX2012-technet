---
title: LoyaltyCardTier.ValidFrom Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ValidFrom Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTier.ValidFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtier.validfrom(v=AX.60)
ms:contentKeyID: 62202023
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTier.ValidFrom
dev_langs:
- CSharp
- C++
- VB
---

# ValidFrom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the start date of the valid period.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ValidFrom As DateTime
    Get
    Set
'Usage
Dim instance As LoyaltyCardTier
Dim value As DateTime

value = instance.ValidFrom

instance.ValidFrom = value
```

``` csharp
[DataMemberAttribute]
public DateTime ValidFrom { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime ValidFrom {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTier Class](loyaltycardtier-class-microsoft-dynamics-retail-sharepoint-web-services-viewmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)

