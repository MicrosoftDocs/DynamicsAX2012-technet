---
title: IRoundingV1.RoundQuantity Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RoundQuantity Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundQuantity(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.roundquantity(v=AX.60)
ms:contentKeyID: 47344025
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundQuantity
dev_langs:
- CSharp
- C++
- VB
---

# RoundQuantity Method

Returns the quantity rounded to the correct amount of decimals.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RoundQuantity ( _
    value As Decimal, _
    unitId As String _
) As String
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim unitId As String
Dim returnValue As String

returnValue = instance.RoundQuantity(value, _
    unitId)
```

``` csharp
string RoundQuantity(
    decimal value,
    string unitId
)
```

``` c++
String^ RoundQuantity(
    Decimal value, 
    String^ unitId
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - unitId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The quantity rounded to the correct amount of decimals, corresponding to the settings in the Unit table.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

