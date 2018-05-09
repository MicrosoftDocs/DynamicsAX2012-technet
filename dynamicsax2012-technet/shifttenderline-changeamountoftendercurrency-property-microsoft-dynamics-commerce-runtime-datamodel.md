---
title: ShiftTenderLine.ChangeAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ChangeAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.changeamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62214913
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ChangeAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ChangeAmountOfTenderCurrency Property

Gets or sets change amount of tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHANGEAMOUNTCUR")> _
<DataMemberAttribute> _
Public Property ChangeAmountOfTenderCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.ChangeAmountOfTenderCurrency

instance.ChangeAmountOfTenderCurrency = value
```

``` csharp
[ColumnAttribute("CHANGEAMOUNTCUR")]
[DataMemberAttribute]
public decimal ChangeAmountOfTenderCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"CHANGEAMOUNTCUR")]
[DataMemberAttribute]
public:
property Decimal ChangeAmountOfTenderCurrency {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

