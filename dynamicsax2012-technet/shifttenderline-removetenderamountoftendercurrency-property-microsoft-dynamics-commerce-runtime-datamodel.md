---
title: ShiftTenderLine.RemoveTenderAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RemoveTenderAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveTenderAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.removetenderamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62209577
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveTenderAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# RemoveTenderAmountOfTenderCurrency Property

Gets or sets amount removed from tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("REMOVETENDERAMOUNTCUR")> _
Public Property RemoveTenderAmountOfTenderCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.RemoveTenderAmountOfTenderCurrency

instance.RemoveTenderAmountOfTenderCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("REMOVETENDERAMOUNTCUR")]
public decimal RemoveTenderAmountOfTenderCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"REMOVETENDERAMOUNTCUR")]
public:
property Decimal RemoveTenderAmountOfTenderCurrency {
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

