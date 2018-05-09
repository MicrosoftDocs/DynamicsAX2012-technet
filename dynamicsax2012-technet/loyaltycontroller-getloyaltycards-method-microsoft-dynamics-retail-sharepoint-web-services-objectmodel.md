---
title: LoyaltyController.GetLoyaltyCards Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GetLoyaltyCards Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GetLoyaltyCards
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.loyaltycontroller.getloyaltycards(v=AX.60)
ms:contentKeyID: 62202938
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GetLoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCards Method

Gets a read only collection with all loyalty card objects

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetLoyaltyCards As ReadOnlyCollection(Of LoyaltyCard)
'Usage
Dim returnValue As ReadOnlyCollection(Of LoyaltyCard)

returnValue = LoyaltyController.GetLoyaltyCards()
```

``` csharp
public static ReadOnlyCollection<LoyaltyCard> GetLoyaltyCards()
```

``` c++
public:
static ReadOnlyCollection<LoyaltyCard^>^ GetLoyaltyCards()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<LoyaltyCard\>  
read only collection of all loyalty card numbers  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

