---
title: ISalesOrderV3.CalculateCancellationChargeTax Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateCancellationChargeTax Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV3.CalculateCancellationChargeTax(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv3.calculatecancellationchargetax(v=AX.60)
ms:contentKeyID: 51677230
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV3.CalculateCancellationChargeTax
dev_langs:
- CSharp
- C++
- VB
---

# CalculateCancellationChargeTax Method

Calculate the tax of cancellation charge for this sales order

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CalculateCancellationChargeTax ( _
    retailTransaction As IRetailTransaction _
) As Decimal
'Usage
Dim instance As ISalesOrderV3
Dim retailTransaction As IRetailTransaction
Dim returnValue As Decimal

returnValue = instance.CalculateCancellationChargeTax(retailTransaction)
```

``` csharp
decimal CalculateCancellationChargeTax(
    IRetailTransaction retailTransaction
)
```

``` c++
Decimal CalculateCancellationChargeTax(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ISalesOrderV3 Interface](isalesorderv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

