---
title: IDiscountV2.AddLoyaltyDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV2.AddLoyaltyDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv2.addloyaltydiscountamount(v=AX.60)
ms:contentKeyID: 62203502
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV2.AddLoyaltyDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# AddLoyaltyDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Add the loyalty discount amount granted on the total transaction amount using loyalty points

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddLoyaltyDiscountAmount ( _
    retailTransaction As IRetailTransaction, _
    amountValue As Decimal _
)
'Usage
Dim instance As IDiscountV2
Dim retailTransaction As IRetailTransaction
Dim amountValue As Decimal

instance.AddLoyaltyDiscountAmount(retailTransaction, _
    amountValue)
```

``` csharp
void AddLoyaltyDiscountAmount(
    IRetailTransaction retailTransaction,
    decimal amountValue
)
```

``` c++
void AddLoyaltyDiscountAmount(
    IRetailTransaction^ retailTransaction, 
    Decimal amountValue
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amountValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[IDiscountV2 Interface](idiscountv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

