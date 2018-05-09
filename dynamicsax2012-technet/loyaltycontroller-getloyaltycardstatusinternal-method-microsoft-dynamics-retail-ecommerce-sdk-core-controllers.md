---
title: LoyaltyController.GetLoyaltyCardStatusInternal Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetLoyaltyCardStatusInternal Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardStatusInternal(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.getloyaltycardstatusinternal(v=AX.60)
ms:contentKeyID: 65316577
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardStatusInternal
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatusInternal Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetLoyaltyCardStatusInternal ( _
    loyaltyCardNumber As String _
) As LoyaltyCard
'Usage
Dim loyaltyCardNumber As String
Dim returnValue As LoyaltyCard

returnValue = Me.GetLoyaltyCardStatusInternal(loyaltyCardNumber)
```

``` csharp
protected virtual LoyaltyCard GetLoyaltyCardStatusInternal(
    string loyaltyCardNumber
)
```

``` c++
protected:
virtual LoyaltyCard^ GetLoyaltyCardStatusInternal(
    String^ loyaltyCardNumber
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: LoyaltyCard  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

