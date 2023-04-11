---
title: LoyaltyController.GetAllLoyaltyCardsStatusInternal Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetAllLoyaltyCardsStatusInternal Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetAllLoyaltyCardsStatusInternal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.getallloyaltycardsstatusinternal(v=AX.60)
ms:contentKeyID: 65317888
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetAllLoyaltyCardsStatusInternal
dev_langs:
- CSharp
- C++
- VB
---

# GetAllLoyaltyCardsStatusInternal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetAllLoyaltyCardsStatusInternal ( _
    customerId As String _
) As ReadOnlyCollection(Of LoyaltyCard)
'Usage
Dim customerId As String
Dim returnValue As ReadOnlyCollection(Of LoyaltyCard)

returnValue = Me.GetAllLoyaltyCardsStatusInternal(customerId)
```

``` csharp
protected virtual ReadOnlyCollection<LoyaltyCard> GetAllLoyaltyCardsStatusInternal(
    string customerId
)
```

``` c++
protected:
virtual ReadOnlyCollection<LoyaltyCard^>^ GetAllLoyaltyCardsStatusInternal(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<LoyaltyCard\>  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

