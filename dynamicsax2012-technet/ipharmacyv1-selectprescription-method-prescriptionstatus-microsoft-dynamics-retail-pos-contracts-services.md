---
title: IPharmacyV1.SelectPrescription Method (PrescriptionStatus) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SelectPrescription Method (PrescriptionStatus)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.SelectPrescription(Microsoft.Dynamics.Retail.Pos.Contracts.Services.PrescriptionStatus)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.selectprescription(v=AX.60)
ms:contentKeyID: 47344494
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SelectPrescription Method (PrescriptionStatus)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Selects a prescription from a list of all valid prescriptions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SelectPrescription ( _
    prescriptionStatus As PrescriptionStatus _
) As String
'Usage
Dim instance As IPharmacyV1
Dim prescriptionStatus As PrescriptionStatus
Dim returnValue As String

returnValue = instance.SelectPrescription(prescriptionStatus)
```

``` csharp
string SelectPrescription(
    PrescriptionStatus prescriptionStatus
)
```

``` c++
String^ SelectPrescription(
    PrescriptionStatus prescriptionStatus
)
```

#### Parameters

  - prescriptionStatus  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PrescriptionStatus](prescriptionstatus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The selected prescription ID.  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[SelectPrescription Overload](ipharmacyv1-selectprescription-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

