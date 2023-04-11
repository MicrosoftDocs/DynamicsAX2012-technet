---
title: IPharmacyV1.IsPrescriptionFound Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IsPrescriptionFound Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.IsPrescriptionFound(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipharmacyv1.isprescriptionfound(v=AX.60)
ms:contentKeyID: 47344451
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPharmacyV1.IsPrescriptionFound
dev_langs:
- CSharp
- C++
- VB
---

# IsPrescriptionFound Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is the prescriptiond ID found in the database.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsPrescriptionFound ( _
    prescriptionId As String _
) As Boolean
'Usage
Dim instance As IPharmacyV1
Dim prescriptionId As String
Dim returnValue As Boolean

returnValue = instance.IsPrescriptionFound(prescriptionId)
```

``` csharp
bool IsPrescriptionFound(
    string prescriptionId
)
```

``` c++
bool IsPrescriptionFound(
    String^ prescriptionId
)
```

#### Parameters

  - prescriptionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if a prescription ID is found; otherwise, false.  

## See Also

#### Reference

[IPharmacyV1 Interface](ipharmacyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

