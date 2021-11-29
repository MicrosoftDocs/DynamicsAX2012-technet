---
title: ShiftTenderLine.DeclareTenderAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeclareTenderAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.DeclareTenderAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.declaretenderamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62211383
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.DeclareTenderAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# DeclareTenderAmountOfStoreCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets declared amount of tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DECLARETENDERAMOUNT")> _
<DataMemberAttribute> _
Public Property DeclareTenderAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.DeclareTenderAmountOfStoreCurrency

instance.DeclareTenderAmountOfStoreCurrency = value
```

``` csharp
[ColumnAttribute("DECLARETENDERAMOUNT")]
[DataMemberAttribute]
public decimal DeclareTenderAmountOfStoreCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"DECLARETENDERAMOUNT")]
[DataMemberAttribute]
public:
property Decimal DeclareTenderAmountOfStoreCurrency {
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

