---
title: ShiftTenderLine.ChangeAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChangeAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ChangeAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.changeamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62206269
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.ChangeAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# ChangeAmountOfStoreCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets change amount of tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CHANGEAMOUNT")> _
<DataMemberAttribute> _
Public Property ChangeAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.ChangeAmountOfStoreCurrency

instance.ChangeAmountOfStoreCurrency = value
```

``` csharp
[ColumnAttribute("CHANGEAMOUNT")]
[DataMemberAttribute]
public decimal ChangeAmountOfStoreCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"CHANGEAMOUNT")]
[DataMemberAttribute]
public:
property Decimal ChangeAmountOfStoreCurrency {
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

