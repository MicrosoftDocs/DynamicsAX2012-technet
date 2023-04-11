---
title: ITaxV2.GetTaxRegime Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetTaxRegime Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxV2.GetTaxRegime(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.itaxv2.gettaxregime(v=AX.60)
ms:contentKeyID: 49850207
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ITaxV2.GetTaxRegime
dev_langs:
- CSharp
- C++
- VB
---

# GetTaxRegime Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetTaxRegime ( _
    address As IAddress _
) As String
'Usage
Dim instance As ITaxV2
Dim address As IAddress
Dim returnValue As String

returnValue = instance.GetTaxRegime(address)
```

``` csharp
string GetTaxRegime(
    IAddress address
)
```

``` c++
String^ GetTaxRegime(
    IAddress^ address
)
```

#### Parameters

  - address  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddress](iaddress-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ITaxV2 Interface](itaxv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

