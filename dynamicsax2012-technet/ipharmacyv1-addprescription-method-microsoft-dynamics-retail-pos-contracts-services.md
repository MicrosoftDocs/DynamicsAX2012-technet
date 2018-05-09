---
title: IPharmacyV1.AddPrescription Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: AddPrescription Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.AddPrescription(System.String,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.addprescription(v=AX.60)
ms:contentKeyID: 47343892
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.AddPrescription
dev_langs:
- CSharp
- C++
- VB
---

# AddPrescription Method

Adds a prescription to a retail transactions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub AddPrescription ( _
    prescriptionId As String, _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As IPharmacyV1
Dim prescriptionId As String
Dim retailTransaction As IRetailTransaction

instance.AddPrescription(prescriptionId, _
    retailTransaction)
```

``` csharp
void AddPrescription(
    string prescriptionId,
    IRetailTransaction retailTransaction
)
```

``` c++
void AddPrescription(
    String^ prescriptionId, 
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - prescriptionId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

