---
title: IRoundingV1.RoundForDisplay Method (Decimal, Boolean, Boolean) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: RoundForDisplay Method (Decimal, Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.RoundForDisplay(System.Decimal,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.roundfordisplay(v=AX.60)
ms:contentKeyID: 47344122
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# RoundForDisplay Method (Decimal, Boolean, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Rounding for display: If no decimal places then sales rounding is used otherwise the amount rounding is used.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function RoundForDisplay ( _
    value As Decimal, _
    useCurrencySymbol As Boolean, _
    useSalesRounding As Boolean _
) As String
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim useCurrencySymbol As Boolean
Dim useSalesRounding As Boolean
Dim returnValue As String

returnValue = instance.RoundForDisplay(value, _
    useCurrencySymbol, useSalesRounding)
```

``` csharp
string RoundForDisplay(
    decimal value,
    bool useCurrencySymbol,
    bool useSalesRounding
)
```

``` c++
String^ RoundForDisplay(
    Decimal value, 
    bool useCurrencySymbol, 
    bool useSalesRounding
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - useCurrencySymbol  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - useSalesRounding  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Formated display string.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[RoundForDisplay Overload](iroundingv1-roundfordisplay-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

