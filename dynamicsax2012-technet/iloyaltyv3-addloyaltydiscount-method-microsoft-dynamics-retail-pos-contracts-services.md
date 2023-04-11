---
title: ILoyaltyV3.AddLoyaltyDiscount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddLoyaltyDiscount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV3.AddLoyaltyDiscount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv3.addloyaltydiscount(v=AX.60)
ms:contentKeyID: 62202221
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV3.AddLoyaltyDiscount
dev_langs:
- CSharp
- C++
- VB
---

# AddLoyaltyDiscount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Adds loyalty discount to the transaction. User is prompted to enter loyalty card number and discount amount.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AddLoyaltyDiscount ( _
    retailTransaction As IRetailTransaction, _
    cardNumber As String, _
    discountAmount As Decimal _
) As Boolean
'Usage
Dim instance As ILoyaltyV3
Dim retailTransaction As IRetailTransaction
Dim cardNumber As String
Dim discountAmount As Decimal
Dim returnValue As Boolean

returnValue = instance.AddLoyaltyDiscount(retailTransaction, _
    cardNumber, discountAmount)
```

``` csharp
bool AddLoyaltyDiscount(
    IRetailTransaction retailTransaction,
    string cardNumber,
    decimal discountAmount
)
```

``` c++
bool AddLoyaltyDiscount(
    IRetailTransaction^ retailTransaction, 
    String^ cardNumber, 
    Decimal discountAmount
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - discountAmount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if loyalty discount added to the transaction  

## See Also

#### Reference

[ILoyaltyV3 Interface](iloyaltyv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

