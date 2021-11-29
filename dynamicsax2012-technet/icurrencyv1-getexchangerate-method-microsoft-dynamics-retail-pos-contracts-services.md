---
title: ICurrencyV1.GetExchangeRate Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetExchangeRate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.GetExchangeRate(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icurrencyv1.getexchangerate(v=AX.60)
ms:contentKeyID: 47344178
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.GetExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# GetExchangeRate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the exchange rate for a given pair of currencies.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetExchangeRate ( _
    fromCurrency As String, _
    toCurrency As String _
) As Decimal
'Usage
Dim instance As ICurrencyV1
Dim fromCurrency As String
Dim toCurrency As String
Dim returnValue As Decimal

returnValue = instance.GetExchangeRate(fromCurrency, _
    toCurrency)
```

``` csharp
decimal GetExchangeRate(
    string fromCurrency,
    string toCurrency
)
```

``` c++
Decimal GetExchangeRate(
    String^ fromCurrency, 
    String^ toCurrency
)
```

#### Parameters

  - fromCurrency  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrency  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The exchange rate returned is divided by 100 and must be multiplied.  

## See Also

#### Reference

[ICurrencyV1 Interface](icurrencyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

