---
title: ITenderLineItemV1.CurrencyCode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: CurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.CurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv1.currencycode(v=AX.60)
ms:contentKeyID: 49837046
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV1.CurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The code to identify the currency.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property CurrencyCode As String
    Get
    Set
'Usage
Dim instance As ITenderLineItemV1
Dim value As String

value = instance.CurrencyCode

instance.CurrencyCode = value
```

``` csharp
string CurrencyCode { get; set; }
```

``` c++
property String^ CurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV1 Interface](itenderlineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

