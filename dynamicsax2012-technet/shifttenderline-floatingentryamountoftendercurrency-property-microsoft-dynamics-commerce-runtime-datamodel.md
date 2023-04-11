---
title: ShiftTenderLine.FloatingEntryAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FloatingEntryAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.FloatingEntryAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.floatingentryamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62208835
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.FloatingEntryAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# FloatingEntryAmountOfTenderCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets float entry of tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ADDTOTENDERAMOUNTCUR")> _
Public Property FloatingEntryAmountOfTenderCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.FloatingEntryAmountOfTenderCurrency

instance.FloatingEntryAmountOfTenderCurrency = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ADDTOTENDERAMOUNTCUR")]
public decimal FloatingEntryAmountOfTenderCurrency { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ADDTOTENDERAMOUNTCUR")]
public:
property Decimal FloatingEntryAmountOfTenderCurrency {
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

