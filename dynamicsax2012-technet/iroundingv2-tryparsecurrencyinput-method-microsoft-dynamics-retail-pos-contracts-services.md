---
title: IRoundingV2.TryParseCurrencyInput Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TryParseCurrencyInput Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV2.TryParseCurrencyInput(System.String,System.String,System.Decimal@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv2.tryparsecurrencyinput(v=AX.60)
ms:contentKeyID: 49822644
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV2.TryParseCurrencyInput
dev_langs:
- CSharp
- C++
- VB
---

# TryParseCurrencyInput Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts the string representation of a number input by a user to its System.Decimal equivalent based on how a decimal separator is treated as input in the system.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TryParseCurrencyInput ( _
    s As String, _
    currencyCode As String, _
    <OutAttribute> ByRef value As Decimal _
) As Boolean
'Usage
Dim instance As IRoundingV2
Dim s As String
Dim currencyCode As String
Dim value As Decimal
Dim returnValue As Boolean

returnValue = instance.TryParseCurrencyInput(s, _
    currencyCode, value)
```

``` csharp
bool TryParseCurrencyInput(
    string s,
    string currencyCode,
    out decimal value
)
```

``` c++
bool TryParseCurrencyInput(
    String^ s, 
    String^ currencyCode, 
    [OutAttribute] Decimal% value
)
```

#### Parameters

  - s  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if parsing was successful, false otherwise  

## Remarks

"100" could parse as 100 or 1.00

## See Also

#### Reference

[IRoundingV2 Interface](iroundingv2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

