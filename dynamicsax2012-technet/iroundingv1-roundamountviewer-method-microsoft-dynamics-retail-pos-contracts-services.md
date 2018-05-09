---
title: IRoundingV1.RoundAmountViewer Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RoundAmountViewer Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundAmountViewer(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.roundamountviewer(v=AX.60)
ms:contentKeyID: 47344500
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundAmountViewer
dev_langs:
- CSharp
- C++
- VB
---

# RoundAmountViewer Method

Rounds amount viewer.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RoundAmountViewer ( _
    amount As Decimal _
) As String
'Usage
Dim instance As IRoundingV1
Dim amount As Decimal
Dim returnValue As String

returnValue = instance.RoundAmountViewer(amount)
```

``` csharp
string RoundAmountViewer(
    decimal amount
)
```

``` c++
String^ RoundAmountViewer(
    Decimal amount
)
```

#### Parameters

  - amount  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Converts amount to string that is based on the smallest currency unit of the amount.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

