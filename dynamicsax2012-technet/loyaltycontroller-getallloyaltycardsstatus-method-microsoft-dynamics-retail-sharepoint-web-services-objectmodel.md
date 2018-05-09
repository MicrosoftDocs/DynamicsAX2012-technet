---
title: LoyaltyController.GetAllLoyaltyCardsStatus Method  (Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel)
TOCTitle: GetAllLoyaltyCardsStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GetAllLoyaltyCardsStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.sharepoint.web.services.objectmodel.loyaltycontroller.getallloyaltycardsstatus(v=AX.60)
ms:contentKeyID: 62201926
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel.LoyaltyController.GetAllLoyaltyCardsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetAllLoyaltyCardsStatus Method

Gets a read only collection of all loyalty card with their status

**Namespace:**  [Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.SP.Web.Services (in Microsoft.Dynamics.Retail.SP.Web.Services.dll)

## Syntax

``` vb
'Declaration
Public Shared Function GetAllLoyaltyCardsStatus As ReadOnlyCollection(Of LoyaltyCard)
'Usage
Dim returnValue As ReadOnlyCollection(Of LoyaltyCard)

returnValue = LoyaltyController.GetAllLoyaltyCardsStatus()
```

``` csharp
public static ReadOnlyCollection<LoyaltyCard> GetAllLoyaltyCardsStatus()
```

``` c++
public:
static ReadOnlyCollection<LoyaltyCard^>^ GetAllLoyaltyCardsStatus()
```

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<LoyaltyCard\>  
Read only collection of all loyalty card with their status  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-sharepoint-web-services-objectmodel.md)

[Microsoft.Dynamics.Retail.SharePoint.Web.Services.ObjectModel Namespace](microsoft-dynamics-retail-sharepoint-web-services-objectmodel-namespace.md)

