---
title: LoyaltyController.GetLoyaltyCards Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetLoyaltyCards Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCards(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.getloyaltycards(v=AX.60)
ms:contentKeyID: 65318310
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCards
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCards Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetLoyaltyCards ( _
    customerId As String _
) As ReadOnlyCollection(Of LoyaltyCard)
'Usage
Dim instance As LoyaltyController
Dim customerId As String
Dim returnValue As ReadOnlyCollection(Of LoyaltyCard)

returnValue = instance.GetLoyaltyCards(customerId)
```

``` csharp
public virtual ReadOnlyCollection<LoyaltyCard> GetLoyaltyCards(
    string customerId
)
```

``` c++
public:
virtual ReadOnlyCollection<LoyaltyCard^>^ GetLoyaltyCards(
    String^ customerId
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[LoyaltyCard](loyaltycard-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

