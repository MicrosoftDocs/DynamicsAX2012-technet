---
title: ILoyaltyV4.AddLoyaltyPayment Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyPayment Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.AddLoyaltyPayment(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv4.addloyaltypayment(v=AX.60)
ms:contentKeyID: 62202955
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.AddLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# AddLoyaltyPayment Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds loyalty payment to the transaction. User is prompted to enter loyalty card number and amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddLoyaltyPayment ( _
    retailTransaction As IRetailTransaction, _
    tenderID As String _
)
'Usage
Dim instance As ILoyaltyV4
Dim retailTransaction As IRetailTransaction
Dim tenderID As String

instance.AddLoyaltyPayment(retailTransaction, _
    tenderID)
```

``` csharp
void AddLoyaltyPayment(
    IRetailTransaction retailTransaction,
    string tenderID
)
```

``` c++
void AddLoyaltyPayment(
    IRetailTransaction^ retailTransaction, 
    String^ tenderID
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - tenderID  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

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
<td><p>Throws exception if retailTransaction is null.</p>
<p>-or-</p>
<p>Throws exception if tenderID is null.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ILoyaltyV4 Interface](iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

