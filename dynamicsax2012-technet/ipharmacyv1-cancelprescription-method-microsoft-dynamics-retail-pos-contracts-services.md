---
title: IPharmacyV1.CancelPrescription Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CancelPrescription Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.CancelPrescription(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.cancelprescription(v=AX.60)
ms:contentKeyID: 47344168
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.CancelPrescription
dev_langs:
- CSharp
- C++
- VB
---

# CancelPrescription Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Cancels the prescription in the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CancelPrescription ( _
    prescriptionId As String, _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As IPharmacyV1
Dim prescriptionId As String
Dim retailTransaction As IRetailTransaction

instance.CancelPrescription(prescriptionId, _
    retailTransaction)
```

``` csharp
void CancelPrescription(
    string prescriptionId,
    IRetailTransaction retailTransaction
)
```

``` c++
void CancelPrescription(
    String^ prescriptionId, 
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - prescriptionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

