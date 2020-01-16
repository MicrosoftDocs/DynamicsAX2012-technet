---
title: ShiftTenderLine.FloatingEntryAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FloatingEntryAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.FloatingEntryAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.floatingentryamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62206691
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.FloatingEntryAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# FloatingEntryAmountOfStoreCurrency Property

Gets or sets float entry of tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ADDTOTENDERAMOUNT")> _
Public Property FloatingEntryAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.FloatingEntryAmountOfStoreCurrency

instance.FloatingEntryAmountOfStoreCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ADDTOTENDERAMOUNT")]
public decimal FloatingEntryAmountOfStoreCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ADDTOTENDERAMOUNT")]
public:
property Decimal FloatingEntryAmountOfStoreCurrency {
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

