---
title: ShiftTenderLine.SafeDropAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SafeDropAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.SafeDropAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.safedropamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62210184
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.SafeDropAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# SafeDropAmountOfStoreCurrency Property

Gets or sets safe drop amount of tender in store curreny.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SAFEDROPAMOUNT")> _
<DataMemberAttribute> _
Public Property SafeDropAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.SafeDropAmountOfStoreCurrency

instance.SafeDropAmountOfStoreCurrency = value
```

``` csharp
[ColumnAttribute("SAFEDROPAMOUNT")]
[DataMemberAttribute]
public decimal SafeDropAmountOfStoreCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"SAFEDROPAMOUNT")]
[DataMemberAttribute]
public:
property Decimal SafeDropAmountOfStoreCurrency {
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

