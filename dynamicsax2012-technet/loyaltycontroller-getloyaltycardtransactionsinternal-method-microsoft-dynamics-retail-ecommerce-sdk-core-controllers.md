---
title: LoyaltyController.GetLoyaltyCardTransactionsInternal Method  (Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers)
TOCTitle: GetLoyaltyCardTransactionsInternal Method
ms:assetid: M:Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardTransactionsInternal(System.String,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.ecommerce.sdk.core.controllers.loyaltycontroller.getloyaltycardtransactionsinternal(v=AX.60)
ms:contentKeyID: 65315776
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers.LoyaltyController.GetLoyaltyCardTransactionsInternal
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyCardTransactionsInternal Method

**Namespace:**  [Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core (in Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.dll)

## Syntax

``` vb
'Declaration
Protected Overridable Function GetLoyaltyCardTransactionsInternal ( _
    loyaltyCardNumber As String, _
    rewardPointId As String, _
    topRows As Integer _
) As PagedResult(Of LoyaltyCardTransaction)
'Usage
Dim loyaltyCardNumber As String
Dim rewardPointId As String
Dim topRows As Integer
Dim returnValue As PagedResult(Of LoyaltyCardTransaction)

returnValue = Me.GetLoyaltyCardTransactionsInternal(loyaltyCardNumber, _
    rewardPointId, topRows)
```

``` csharp
protected virtual PagedResult<LoyaltyCardTransaction> GetLoyaltyCardTransactionsInternal(
    string loyaltyCardNumber,
    string rewardPointId,
    int topRows
)
```

``` c++
protected:
virtual PagedResult<LoyaltyCardTransaction^>^ GetLoyaltyCardTransactionsInternal(
    String^ loyaltyCardNumber, 
    String^ rewardPointId, 
    int topRows
)
```

#### Parameters

  - loyaltyCardNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - rewardPointId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - topRows  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: PagedResult\<LoyaltyCardTransaction\>  

## See Also

#### Reference

[LoyaltyController Class](loyaltycontroller-class-microsoft-dynamics-retail-ecommerce-sdk-core-controllers.md)

[Microsoft.Dynamics.Retail.Ecommerce.Sdk.Core.Controllers Namespace](microsoft-dynamics-retail-ecommerce-sdk-core-controllers-namespace.md)

