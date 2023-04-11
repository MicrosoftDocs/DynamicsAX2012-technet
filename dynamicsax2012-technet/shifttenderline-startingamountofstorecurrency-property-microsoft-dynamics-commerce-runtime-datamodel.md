---
title: ShiftTenderLine.StartingAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StartingAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.StartingAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.startingamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62212727
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.StartingAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# StartingAmountOfStoreCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets starting amount of tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STARTINGAMOUNT")> _
<DataMemberAttribute> _
Public Property StartingAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.StartingAmountOfStoreCurrency

instance.StartingAmountOfStoreCurrency = value
```

``` csharp
[ColumnAttribute("STARTINGAMOUNT")]
[DataMemberAttribute]
public decimal StartingAmountOfStoreCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"STARTINGAMOUNT")]
[DataMemberAttribute]
public:
property Decimal StartingAmountOfStoreCurrency {
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

