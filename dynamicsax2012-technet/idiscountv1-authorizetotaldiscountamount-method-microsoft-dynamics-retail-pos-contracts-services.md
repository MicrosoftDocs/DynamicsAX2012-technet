---
title: IDiscountV1.AuthorizeTotalDiscountAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeTotalDiscountAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeTotalDiscountAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.authorizetotaldiscountamount(v=AX.60)
ms:contentKeyID: 47343837
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeTotalDiscountAmount
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeTotalDiscountAmount Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the given total discount amount is allowed.

This method is invoked by the total discount percentage operation before calling the AddTotalDiscountAmount method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeTotalDiscountAmount ( _
    retailTransaction As IRetailTransaction, _
    amountValue As Decimal, _
    maxAmountValue As Decimal _
) As Boolean
'Usage
Dim instance As IDiscountV1
Dim retailTransaction As IRetailTransaction
Dim amountValue As Decimal
Dim maxAmountValue As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeTotalDiscountAmount(retailTransaction, _
    amountValue, maxAmountValue)
```

``` csharp
bool AuthorizeTotalDiscountAmount(
    IRetailTransaction retailTransaction,
    decimal amountValue,
    decimal maxAmountValue
)
```

``` c++
bool AuthorizeTotalDiscountAmount(
    IRetailTransaction^ retailTransaction, 
    Decimal amountValue, 
    Decimal maxAmountValue
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - amountValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - maxAmountValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if total discount amount is allowed otherwise, false.  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

