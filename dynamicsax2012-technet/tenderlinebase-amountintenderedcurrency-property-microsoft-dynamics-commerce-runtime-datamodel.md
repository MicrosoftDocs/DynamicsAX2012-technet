---
title: TenderLineBase.AmountInTenderedCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AmountInTenderedCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.AmountInTenderedCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tenderlinebase.amountintenderedcurrency(v=AX.60)
ms:contentKeyID: 62208374
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderLineBase.AmountInTenderedCurrency
dev_langs:
- CSharp
- C++
- VB
---

# AmountInTenderedCurrency Property

Gets or sets the amount in tendered currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AMOUNTINTENDEREDCURRENCY")> _
Public Property AmountInTenderedCurrency As Decimal
    Get
    Set
'Usage
Dim instance As TenderLineBase
Dim value As Decimal

value = instance.AmountInTenderedCurrency

instance.AmountInTenderedCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AMOUNTINTENDEREDCURRENCY")]
public decimal AmountInTenderedCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AMOUNTINTENDEREDCURRENCY")]
public:
property Decimal AmountInTenderedCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The amount in tendered currency.  

## See Also

#### Reference

[TenderLineBase Class](tenderlinebase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

