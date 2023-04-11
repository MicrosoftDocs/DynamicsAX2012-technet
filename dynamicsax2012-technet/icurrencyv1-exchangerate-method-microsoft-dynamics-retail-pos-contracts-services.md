---
title: ICurrencyV1.ExchangeRate Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ExchangeRate Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.ExchangeRate(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icurrencyv1.exchangerate(v=AX.60)
ms:contentKeyID: 47344410
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICurrencyV1.ExchangeRate
dev_langs:
- CSharp
- C++
- VB
---

# ExchangeRate Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Returns the latest currency exchange rate against the default currency for a given currency code.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ExchangeRate ( _
    currencyCode As String _
) As Decimal
'Usage
Dim instance As ICurrencyV1
Dim currencyCode As String
Dim returnValue As Decimal

returnValue = instance.ExchangeRate(currencyCode)
```

``` csharp
decimal ExchangeRate(
    string currencyCode
)
```

``` c++
Decimal ExchangeRate(
    String^ currencyCode
)
```

#### Parameters

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The currency exchange rate.  

## See Also

#### Reference

[ICurrencyV1 Interface](icurrencyv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

