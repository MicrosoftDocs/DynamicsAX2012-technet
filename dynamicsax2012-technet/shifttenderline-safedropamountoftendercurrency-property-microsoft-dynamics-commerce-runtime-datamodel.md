---
title: ShiftTenderLine.SafeDropAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SafeDropAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.SafeDropAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.safedropamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62212335
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.SafeDropAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# SafeDropAmountOfTenderCurrency Property

Gets or sets safe drop amount of tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SAFEDROPAMOUNTCUR")> _
<DataMemberAttribute> _
Public Property SafeDropAmountOfTenderCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.SafeDropAmountOfTenderCurrency

instance.SafeDropAmountOfTenderCurrency = value
```

``` csharp
[ColumnAttribute("SAFEDROPAMOUNTCUR")]
[DataMemberAttribute]
public decimal SafeDropAmountOfTenderCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"SAFEDROPAMOUNTCUR")]
[DataMemberAttribute]
public:
property Decimal SafeDropAmountOfTenderCurrency {
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

