---
title: ILoyaltyV1.AddLoyaltyPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.AddLoyaltyPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv1.addloyaltypayment(v=AX.60)
ms:contentKeyID: 47344019
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV1.AddLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# AddLoyaltyPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Called from the pay gift card operation after a check to guarantee that the transaction is the IRetailTransaction type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddLoyaltyPayment ( _
    retailTransaction As IRetailTransaction, _
    cardInfo As ICardInfo, _
    amount As Decimal _
)
'Usage
Dim instance As ILoyaltyV1
Dim retailTransaction As IRetailTransaction
Dim cardInfo As ICardInfo
Dim amount As Decimal

instance.AddLoyaltyPayment(retailTransaction, _
    cardInfo, amount)
```

``` csharp
void AddLoyaltyPayment(
    IRetailTransaction retailTransaction,
    ICardInfo cardInfo,
    decimal amount
)
```

``` c++
void AddLoyaltyPayment(
    IRetailTransaction^ retailTransaction, 
    ICardInfo^ cardInfo, 
    Decimal amount
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Throws if retailTransaction is null.</p>
<p>-or-</p>
<p>Throws if cardInfo is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ILoyaltyV1 Interface](iloyaltyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

