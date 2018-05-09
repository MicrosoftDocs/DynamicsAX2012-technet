---
title: IPharmacyV1.CancelAllPrescriptions Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CancelAllPrescriptions Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.CancelAllPrescriptions(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.cancelallprescriptions(v=AX.60)
ms:contentKeyID: 47344172
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.CancelAllPrescriptions
dev_langs:
- CSharp
- C++
- VB
---

# CancelAllPrescriptions Method

Cancels all the pharmacy prescriptions in the retail transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CancelAllPrescriptions ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As IPharmacyV1
Dim retailTransaction As IRetailTransaction

instance.CancelAllPrescriptions(retailTransaction)
```

``` csharp
void CancelAllPrescriptions(
    IRetailTransaction retailTransaction
)
```

``` c++
void CancelAllPrescriptions(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

