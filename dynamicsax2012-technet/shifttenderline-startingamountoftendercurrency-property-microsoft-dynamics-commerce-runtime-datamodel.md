---
title: ShiftTenderLine.StartingAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StartingAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.StartingAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.startingamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62212310
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.StartingAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# StartingAmountOfTenderCurrency Property

Gets or sets starting amount of tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STARTINGAMOUNTCUR")> _
<DataMemberAttribute> _
Public Property StartingAmountOfTenderCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.StartingAmountOfTenderCurrency

instance.StartingAmountOfTenderCurrency = value
```

``` csharp
[ColumnAttribute("STARTINGAMOUNTCUR")]
[DataMemberAttribute]
public decimal StartingAmountOfTenderCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"STARTINGAMOUNTCUR")]
[DataMemberAttribute]
public:
property Decimal StartingAmountOfTenderCurrency {
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

