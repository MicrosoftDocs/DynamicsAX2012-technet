---
title: ShiftTenderLine.TenderedAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderedAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderedAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.tenderedamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62205968
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderedAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# TenderedAmountOfTenderCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets shift amount of tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TENDEREDAMOUNTCUR")> _
Public Property TenderedAmountOfTenderCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.TenderedAmountOfTenderCurrency

instance.TenderedAmountOfTenderCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TENDEREDAMOUNTCUR")]
public decimal TenderedAmountOfTenderCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TENDEREDAMOUNTCUR")]
public:
property Decimal TenderedAmountOfTenderCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

