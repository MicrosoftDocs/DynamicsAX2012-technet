---
title: LoyaltyController.GetLoyaltyCardTransactions Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetLoyaltyCardTransactions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardTransactions(System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.getloyaltycardtransactions(v=AX.60)
ms:contentKeyID: 65316429
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardTransactions
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactions Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function GetLoyaltyCardTransactions ( _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    topRows As Integer _
) As ReadOnlyCollection(Of LoyaltyCardTransaction)
'Usage
Dim instance As LoyaltyController
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim topRows As Integer
Dim returnValue As ReadOnlyCollection(Of LoyaltyCardTransaction)

returnValue = instance.GetLoyaltyCardTransactions(loyaltyCardNumber, _
    rewardPointId, topRows)
```

``` csharp
public virtual ReadOnlyCollection<LoyaltyCardTransaction> GetLoyaltyCardTransactions(
    string loyaltyCardNumber,
    string rewardPointId,
    int topRows
)
```

``` c++
public:
virtual ReadOnlyCollection<LoyaltyCardTransaction^>^ GetLoyaltyCardTransactions(
    String^ loyaltyCardNumber, 
    String^ rewardPointId, 
    int topRows
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - topRows  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[LoyaltyCardTransaction](loyaltycardtransaction-class-microsoft-dynamics-retail-ecommerce-sdk-core-models.md)\>  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

