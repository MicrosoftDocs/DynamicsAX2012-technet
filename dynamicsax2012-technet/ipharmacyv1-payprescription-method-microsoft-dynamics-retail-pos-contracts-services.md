---
title: IPharmacyV1.PayPrescription Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: PayPrescription Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.PayPrescription(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.payprescription(v=AX.60)
ms:contentKeyID: 47344338
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.PayPrescription
dev_langs:
- CSharp
- C++
- VB
---

# PayPrescription Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Marks the prescription as paid.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function PayPrescription ( _
    retailTransaction As IRetailTransaction _
) As Boolean
'Usage
Dim instance As IPharmacyV1
Dim retailTransaction As IRetailTransaction
Dim returnValue As Boolean

returnValue = instance.PayPrescription(retailTransaction)
```

``` csharp
bool PayPrescription(
    IRetailTransaction retailTransaction
)
```

``` c++
bool PayPrescription(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if the confirmation was successful; otherwise, false.  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

