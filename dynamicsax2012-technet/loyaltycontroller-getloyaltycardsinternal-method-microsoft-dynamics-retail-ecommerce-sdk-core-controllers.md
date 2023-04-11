---
title: LoyaltyController.GetLoyaltyCardsInternal Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetLoyaltyCardsInternal Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardsInternal(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.getloyaltycardsinternal(v=AX.60)
ms:contentKeyID: 65315773
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardsInternal
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardsInternal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetLoyaltyCardsInternal ( _
    customerId As String _
) As ReadOnlyCollection(Of LoyaltyCard)
'Usage
Dim customerId As String
Dim returnValue As ReadOnlyCollection(Of LoyaltyCard)

returnValue = Me.GetLoyaltyCardsInternal(customerId)
```

``` csharp
protected virtual ReadOnlyCollection<LoyaltyCard> GetLoyaltyCardsInternal(
    string customerId
)
```

``` c++
protected:
virtual ReadOnlyCollection<LoyaltyCard^>^ GetLoyaltyCardsInternal(
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

