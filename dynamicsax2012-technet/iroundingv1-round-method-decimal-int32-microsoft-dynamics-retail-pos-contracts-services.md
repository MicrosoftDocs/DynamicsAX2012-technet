---
title: IRoundingV1.Round Method (Decimal, Int32) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Round Method (Decimal, Int32)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.Round(System.Decimal,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.round(v=AX.60)
ms:contentKeyID: 47343824
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Round Method (Decimal, Int32)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Standard round to the minimal coin/amount according to the store currency.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Round ( _
    value As Decimal, _
    numberOfDecimals As Integer _
) As Decimal
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim numberOfDecimals As Integer
Dim returnValue As Decimal

returnValue = instance.Round(value, numberOfDecimals)
```

``` csharp
decimal Round(
    decimal value,
    int numberOfDecimals
)
```

``` c++
Decimal Round(
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

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The rounded value.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Round Overload](iroundingv1-round-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

