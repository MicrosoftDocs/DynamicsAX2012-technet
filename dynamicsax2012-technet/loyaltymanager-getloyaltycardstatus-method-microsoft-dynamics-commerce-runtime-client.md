---
title: LoyaltyManager.GetLoyaltyCardStatus Method  (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetLoyaltyCardStatus Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.GetLoyaltyCardStatus(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.loyaltymanager.getloyaltycardstatus(v=AX.60)
ms:contentKeyID: 62214215
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Client.LoyaltyManager.GetLoyaltyCardStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the status of a loyalty card including card tiers and reward points status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetLoyaltyCardStatus ( _
    loyaltyCardNumber As String _
) As LoyaltyCard
'Usage
Dim instance As LoyaltyManager
Dim loyaltyCardNumber As String
Dim returnValue As LoyaltyCard

returnValue = instance.GetLoyaltyCardStatus(loyaltyCardNumber)
```

``` csharp
public LoyaltyCard GetLoyaltyCardStatus(
    string loyaltyCardNumber
)
```

``` c++
public:
LoyaltyCard^ GetLoyaltyCardStatus(
    String^ loyaltyCardNumber
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The loyalty card containing the card tiers and reward points status.  

## See Also

#### Reference

[LoyaltyManager Class](loyaltymanager-class-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

