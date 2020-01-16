---
title: IRoundingV1.RoundForReceipt Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RoundForReceipt Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundForReceipt(System.Decimal,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.roundforreceipt(v=AX.60)
ms:contentKeyID: 47344384
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundForReceipt
dev_langs:
- CSharp
- C++
- VB
---

# RoundForReceipt Method

Returns the formatted string for receipt displaying.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RoundForReceipt ( _
    value As Decimal, _
    numberOfDecimals As Integer _
) As String
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim numberOfDecimals As Integer
Dim returnValue As String

returnValue = instance.RoundForReceipt(value, _
    numberOfDecimals)
```

``` csharp
string RoundForReceipt(
    decimal value,
    int numberOfDecimals
)
```

``` c++
String^ RoundForReceipt(
    Decimal value, 
    int numberOfDecimals
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - numberOfDecimals  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns formatted string for receipt displaying.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

