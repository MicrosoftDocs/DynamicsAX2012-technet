---
title: IPharmacyV1.SelectPrescription Method (PrescriptionStatus, String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: SelectPrescription Method (PrescriptionStatus, String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.SelectPrescription(Microsoft.Dynamics.Retail.Pos.Contracts.Services.PrescriptionStatus,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.selectprescription(v=AX.60)
ms:contentKeyID: 47343998
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SelectPrescription Method (PrescriptionStatus, String)

Selects a prescription that contains a certain string from a list of all valid prescriptions.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function SelectPrescription ( _
    prescriptionStatus As PrescriptionStatus, _
    rowFilter As String _
) As String
'Usage
Dim instance As IPharmacyV1
Dim prescriptionStatus As PrescriptionStatus
Dim rowFilter As String
Dim returnValue As String

returnValue = instance.SelectPrescription(prescriptionStatus, _
    rowFilter)
```

``` csharp
string SelectPrescription(
    PrescriptionStatus prescriptionStatus,
    string rowFilter
)
```

``` c++
String^ SelectPrescription(
    PrescriptionStatus prescriptionStatus, 
    String^ rowFilter
)
```

#### Parameters

  - prescriptionStatus  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.Services.PrescriptionStatus](prescriptionstatus-enumeration-microsoft-dynamics-retail-pos-contracts-services.md)  

<!-- end list -->

  - rowFilter  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The selected prescription ID.  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[SelectPrescription Overload](ipharmacyv1-selectprescription-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

