---
title: LoyaltyController.GetLoyaltyCardStatus Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GetLoyaltyCardStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GetLoyaltyCardStatus(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.loyaltycontroller.getloyaltycardstatus(v=AX.60)
ms:contentKeyID: 62206279
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GetLoyaltyCardStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a loyalty card with its status

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetLoyaltyCardStatus ( _
    loyaltyCardNumber As String _
) As LoyaltyCard
'Usage
Dim loyaltyCardNumber As String
Dim returnValue As LoyaltyCard

returnValue = LoyaltyController.GetLoyaltyCardStatus(loyaltyCardNumber)
```

``` csharp
public static LoyaltyCard GetLoyaltyCardStatus(
    string loyaltyCardNumber
)
```

``` c++
public:
static LoyaltyCard^ GetLoyaltyCardStatus(
    String^ loyaltyCardNumber
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: LoyaltyCard  
A loyalty card object  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

