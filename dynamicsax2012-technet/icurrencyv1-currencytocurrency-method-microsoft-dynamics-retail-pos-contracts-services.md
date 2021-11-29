---
title: ICurrencyV1.CurrencyToCurrency Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CurrencyToCurrency Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.CurrencyToCurrency(System.String,System.String,System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icurrencyv1.currencytocurrency(v=AX.60)
ms:contentKeyID: 47344238
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.CurrencyToCurrency
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyToCurrency Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts a value from one currency to another.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function CurrencyToCurrency ( _
    fromCurrencyCode As String, _
    toCurrencyCode As String, _
    orgValue As Decimal _
) As Decimal
'Usage
Dim instance As ICurrencyV1
Dim fromCurrencyCode As String
Dim toCurrencyCode As String
Dim orgValue As Decimal
Dim returnValue As Decimal

returnValue = instance.CurrencyToCurrency(fromCurrencyCode, _
    toCurrencyCode, orgValue)
```

``` csharp
decimal CurrencyToCurrency(
    string fromCurrencyCode,
    string toCurrencyCode,
    decimal orgValue
)
```

``` c++
Decimal CurrencyToCurrency(
    String^ fromCurrencyCode, 
    String^ toCurrencyCode, 
    Decimal orgValue
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orgValue  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The value as it is after conversion in the toCurrencyCode parameter rounded according to the toCurrencyCode parameter rounding setup.  

## See Also

#### Reference

[ICurrencyV1 Interface](icurrencyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

