---
title: AttributeCurrencyValue.CurrencyValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CurrencyValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCurrencyValue.CurrencyValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributecurrencyvalue.currencyvalue(v=AX.60)
ms:contentKeyID: 49855211
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeCurrencyValue.CurrencyValue
dev_langs:
- CSharp
- C++
- VB
---

# CurrencyValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the attribute value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CurrencyValue As Decimal
    Get
    Set
'Usage
Dim instance As AttributeCurrencyValue
Dim value As Decimal

value = instance.CurrencyValue

instance.CurrencyValue = value
```

``` csharp
[DataMemberAttribute]
public decimal CurrencyValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal CurrencyValue {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The currency value.  

## See Also

#### Reference

[AttributeCurrencyValue Class](attributecurrencyvalue-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

