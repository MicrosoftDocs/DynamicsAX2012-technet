---
title: IRoundingV1.TaxRound Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TaxRound Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.TaxRound(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.taxround(v=AX.60)
ms:contentKeyID: 47344176
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.TaxRound
dev_langs:
- CSharp
- C++
- VB
---

# TaxRound Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the standard round of the tax amount according to the tax code setup.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TaxRound ( _
    value As Decimal, _
    taxCode As String _
) As Decimal
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim taxCode As String
Dim returnValue As Decimal

returnValue = instance.TaxRound(value, _
    taxCode)
```

``` csharp
decimal TaxRound(
    decimal value,
    string taxCode
)
```

``` c++
Decimal TaxRound(
    Decimal value, 
    String^ taxCode
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - taxCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The rounded value.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

