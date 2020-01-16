---
title: IPharmacyV1.GetPrescriptionList Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetPrescriptionList Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.GetPrescriptionList(Microsoft.Dynamics.Retail.Pos.Contracts.Services.PrescriptionStatus)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.getprescriptionlist(v=AX.60)
ms:contentKeyID: 47344397
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.GetPrescriptionList
dev_langs:
- CSharp
- C++
- VB
---

# GetPrescriptionList Method

Gets a list of prescriptions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetPrescriptionList ( _
    prescriptionStatus As PrescriptionStatus _
) As DataTable
'Usage
Dim instance As IPharmacyV1
Dim prescriptionStatus As PrescriptionStatus
Dim returnValue As DataTable

returnValue = instance.GetPrescriptionList(prescriptionStatus)
```

``` csharp
DataTable GetPrescriptionList(
    PrescriptionStatus prescriptionStatus
)
```

``` c++
DataTable^ GetPrescriptionList(
    PrescriptionStatus prescriptionStatus
)
```

#### Parameters

  - prescriptionStatus  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PrescriptionStatus](prescriptionstatus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [System.Data.DataTable](https://technet.microsoft.com/library/9186hy08\(v=ax.60\))  
Returns a datatable with rows of prescriptions.  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

