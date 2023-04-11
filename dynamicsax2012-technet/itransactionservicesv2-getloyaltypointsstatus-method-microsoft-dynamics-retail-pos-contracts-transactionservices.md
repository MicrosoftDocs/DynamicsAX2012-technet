---
title: ITransactionServicesV2.GetLoyaltyPointsStatus Method  (Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices)
TOCTitle: GetLoyaltyPointsStatus Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV2.GetLoyaltyPointsStatus(System.Boolean@,System.String@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.transactionservices.itransactionservicesv2.getloyaltypointsstatus(v=AX.60)
ms:contentKeyID: 62202545
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices.ITransactionServicesV2.GetLoyaltyPointsStatus
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyPointsStatus Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Note: This API is now obsolete.**

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method has been deprecated. Use the ILoyalty::GetLoyaltyBalanceInfo method instead")> _
Sub GetLoyaltyPointsStatus ( _
    ByRef valid As Boolean, _
    ByRef comment As String, _
    loyaltyCardData As ILoyaltyCardData _
)
'Usage
Dim instance As ITransactionServicesV2
Dim valid As Boolean
Dim comment As String
Dim loyaltyCardData As ILoyaltyCardData

instance.GetLoyaltyPointsStatus(valid, _
    comment, loyaltyCardData)
```

``` csharp
[ObsoleteAttribute("This method has been deprecated. Use the ILoyalty::GetLoyaltyBalanceInfo method instead")]
void GetLoyaltyPointsStatus(
    ref bool valid,
    ref string comment,
    ILoyaltyCardData loyaltyCardData
)
```

``` c++
[ObsoleteAttribute(L"This method has been deprecated. Use the ILoyalty::GetLoyaltyBalanceInfo method instead")]
void GetLoyaltyPointsStatus(
    bool% valid, 
    String^% comment, 
    ILoyaltyCardData^ loyaltyCardData
)
```

#### Parameters

  - valid  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - loyaltyCardData  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData](iloyaltycarddata-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITransactionServicesV2 Interface](itransactionservicesv2-interface-microsoft-dynamics-retail-pos-contracts-transactionservices.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.TransactionServices Namespace](microsoft-dynamics-retail-pos-contracts-transactionservices-namespace.md)

