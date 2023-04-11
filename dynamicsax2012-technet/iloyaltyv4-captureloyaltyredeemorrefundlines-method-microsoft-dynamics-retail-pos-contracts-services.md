---
title: ILoyaltyV4.CaptureLoyaltyRedeemOrRefundLines Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CaptureLoyaltyRedeemOrRefundLines Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.CaptureLoyaltyRedeemOrRefundLines(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv4.captureloyaltyredeemorrefundlines(v=AX.60)
ms:contentKeyID: 62202327
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.CaptureLoyaltyRedeemOrRefundLines
dev_langs:
- CSharp
- C++
- VB
---

# CaptureLoyaltyRedeemOrRefundLines Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Captures loyalty reward point lines for redeem or refund.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CaptureLoyaltyRedeemOrRefundLines ( _
    retailTransaction As IRetailTransaction _
) As Boolean
'Usage
Dim instance As ILoyaltyV4
Dim retailTransaction As IRetailTransaction
Dim returnValue As Boolean

returnValue = instance.CaptureLoyaltyRedeemOrRefundLines(retailTransaction)
```

``` csharp
bool CaptureLoyaltyRedeemOrRefundLines(
    IRetailTransaction retailTransaction
)
```

``` c++
bool CaptureLoyaltyRedeemOrRefundLines(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if loyalty reward lines were captured, false otherwise.  

## See Also

#### Reference

[ILoyaltyV4 Interface](iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

