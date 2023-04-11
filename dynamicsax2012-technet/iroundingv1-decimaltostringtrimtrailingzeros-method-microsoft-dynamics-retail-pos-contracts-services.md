---
title: IRoundingV1.DecimalToStringTrimTrailingZeros Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: DecimalToStringTrimTrailingZeros Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.DecimalToStringTrimTrailingZeros(System.Decimal,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.decimaltostringtrimtrailingzeros(v=AX.60)
ms:contentKeyID: 47343822
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.DecimalToStringTrimTrailingZeros
dev_langs:
- CSharp
- C++
- VB
---

# DecimalToStringTrimTrailingZeros Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts passed amount from decimal to string.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function DecimalToStringTrimTrailingZeros ( _
    amount As Decimal, _
    decimalSep As String _
) As String
'Usage
Dim instance As IRoundingV1
Dim amount As Decimal
Dim decimalSep As String
Dim returnValue As String

returnValue = instance.DecimalToStringTrimTrailingZeros(amount, _
    decimalSep)
```

``` csharp
string DecimalToStringTrimTrailingZeros(
    decimal amount,
    string decimalSep
)
```

``` c++
String^ DecimalToStringTrimTrailingZeros(
    Decimal amount, 
    String^ decimalSep
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - decimalSep  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The string amount.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

