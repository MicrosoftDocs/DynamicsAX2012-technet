---
title: IDiscountV1.AuthorizeTotalDiscountPercent Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AuthorizeTotalDiscountPercent Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeTotalDiscountPercent(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction,System.Decimal,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.idiscountv1.authorizetotaldiscountpercent(v=AX.60)
ms:contentKeyID: 47344413
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IDiscountV1.AuthorizeTotalDiscountPercent
dev_langs:
- CSharp
- C++
- VB
---

# AuthorizeTotalDiscountPercent Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates whether the given discount percentage is allowed.

This method is invoked by the total discount percentage operation before calling the AddTotalDiscountPercentage method.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function AuthorizeTotalDiscountPercent ( _
    retailTransaction As IRetailTransaction, _
    percentValue As Decimal, _
    maxPercentValue As Decimal _
) As Boolean
'Usage
Dim instance As IDiscountV1
Dim retailTransaction As IRetailTransaction
Dim percentValue As Decimal
Dim maxPercentValue As Decimal
Dim returnValue As Boolean

returnValue = instance.AuthorizeTotalDiscountPercent(retailTransaction, _
    percentValue, maxPercentValue)
```

``` csharp
bool AuthorizeTotalDiscountPercent(
    IRetailTransaction retailTransaction,
    decimal percentValue,
    decimal maxPercentValue
)
```

``` c++
bool AuthorizeTotalDiscountPercent(
    IRetailTransaction^ retailTransaction, 
    Decimal percentValue, 
    Decimal maxPercentValue
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - percentValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - maxPercentValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if the discount percentage is allowed; otherwise, false.  

## See Also

#### Reference

[IDiscountV1 Interface](idiscountv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

