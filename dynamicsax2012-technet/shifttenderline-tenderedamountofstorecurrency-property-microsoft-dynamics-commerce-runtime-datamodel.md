---
title: ShiftTenderLine.TenderedAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TenderedAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderedAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.tenderedamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62214920
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TenderedAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# TenderedAmountOfStoreCurrency Property

Gets or sets shift amount of tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TENDEREDAMOUNT")> _
<DataMemberAttribute> _
Public Property TenderedAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.TenderedAmountOfStoreCurrency

instance.TenderedAmountOfStoreCurrency = value
```

``` csharp
[ColumnAttribute("TENDEREDAMOUNT")]
[DataMemberAttribute]
public decimal TenderedAmountOfStoreCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"TENDEREDAMOUNT")]
[DataMemberAttribute]
public:
property Decimal TenderedAmountOfStoreCurrency {
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

