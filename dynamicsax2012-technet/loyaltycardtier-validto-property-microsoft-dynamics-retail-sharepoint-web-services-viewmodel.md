---
title: LoyaltyCardTier.ValidTo Property  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel)
TOCTitle: ValidTo Property
ms:assetid: P:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTier.ValidTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.viewmodel.loyaltycardtier.validto(v=AX.60)
ms:contentKeyID: 62201930
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel.LoyaltyCardTier.ValidTo
dev_langs:
- CSharp
- C++
- VB
---

# ValidTo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the end date of the valid period.

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ViewModel](microsoft-dynamics-retail-sharepoint-web-services-viewmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ValidTo As DateTime
    Get
    Set
'Usage
Dim instance As LoyaltyCardTier
Dim value As DateTime

value = instance.ValidTo

instance.ValidTo = value
```

``` csharp
[DataMemberAttribute]
public DateTime ValidTo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime ValidTo {
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

