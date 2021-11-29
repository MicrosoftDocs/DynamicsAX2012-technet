---
title: IRoundingV1.Round Method (Decimal, String, Boolean) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: Round Method (Decimal, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IRoundingV1.Round(System.Decimal,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iroundingv1.round(v=AX.60)
ms:contentKeyID: 47344431
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Round Method (Decimal, String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Standard round to the minimal coin/amount according to the store currency.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function Round ( _
    value As Decimal, _
    currencyCode As String, _
    useCurrencySymbol As Boolean _
) As String
'Usage
Dim instance As IRoundingV1
Dim value As Decimal
Dim currencyCode As String
Dim useCurrencySymbol As Boolean
Dim returnValue As String

returnValue = instance.Round(value, currencyCode, _
    useCurrencySymbol)
```

``` csharp
string Round(
    decimal value,
    string currencyCode,
    bool useCurrencySymbol
)
```

``` c++
String^ Round(
    Decimal value, 
    String^ currencyCode, 
    bool useCurrencySymbol
)
```

#### Parameters

  - value  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - useCurrencySymbol  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The rounded value as string.  

## See Also

#### Reference

[IRoundingV1 Interface](iroundingv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Round Overload](iroundingv1-round-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

