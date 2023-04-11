---
title: ITaxProviderV1.CalculateTax Method (IRetailTransaction) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CalculateTax Method (IRetailTransaction)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxProviderV1.CalculateTax(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itaxproviderv1.calculatetax(v=AX.60)
ms:contentKeyID: 47344350
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateTax Method (IRetailTransaction)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Calculates tax for all line items on the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CalculateTax ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ITaxProviderV1
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

[ITaxProviderV1 Interface](itaxproviderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[CalculateTax Overload](itaxproviderv1-calculatetax-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

