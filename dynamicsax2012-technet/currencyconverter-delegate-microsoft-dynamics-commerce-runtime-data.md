---
title: CurrencyConverter Delegate (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CurrencyConverter Delegate
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.currencyconverter(v=AX.60)
ms:contentKeyID: 49831374
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CurrencyConverter
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyConverter Delegate

Delegate that takes an amount and currencies to round between.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Delegate Function CurrencyConverter ( _
    fromCurrencyCode As String, _
    toCurrencyCode As String, _
    amountToConvert As Decimal _
) As Decimal
'Usage
Dim instance As New CurrencyConverter(AddressOf HandlerMethod)
```

``` csharp
public delegate decimal CurrencyConverter(
    string fromCurrencyCode,
    string toCurrencyCode,
    decimal amountToConvert
)
```

``` c++
public delegate Decimal CurrencyConverter(
    String^ fromCurrencyCode, 
    String^ toCurrencyCode, 
    Decimal amountToConvert
)
```

#### Parameters

  - fromCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - toCurrencyCode  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - amountToConvert  
    Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

