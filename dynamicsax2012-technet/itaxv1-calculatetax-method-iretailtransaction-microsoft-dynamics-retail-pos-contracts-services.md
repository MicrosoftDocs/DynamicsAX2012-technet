---
title: ITaxV1.CalculateTax Method (IRetailTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateTax Method (IRetailTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxV1.CalculateTax(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.itaxv1.calculatetax(v=AX.60)
ms:contentKeyID: 47344417
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateTax Method (IRetailTransaction)

Calculates the taxes for all lines in the current transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateTax ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ITaxV1
Dim retailTransaction As IRetailTransaction

instance.CalculateTax(retailTransaction)
```

``` csharp
void CalculateTax(
    IRetailTransaction retailTransaction
)
```

``` c++
void CalculateTax(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[ITaxV1 Interface](itaxv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[CalculateTax Overload](itaxv1-calculatetax-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

