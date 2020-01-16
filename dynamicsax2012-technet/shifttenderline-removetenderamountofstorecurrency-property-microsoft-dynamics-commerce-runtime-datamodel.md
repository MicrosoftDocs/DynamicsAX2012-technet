---
title: ShiftTenderLine.RemoveTenderAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RemoveTenderAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveTenderAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.removetenderamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62212826
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveTenderAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# RemoveTenderAmountOfStoreCurrency Property

Gets or sets amount removed from tender in store currency.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("REMOVETENDERAMOUNT")> _
<DataMemberAttribute> _
Public Property RemoveTenderAmountOfStoreCurrency As Decimal
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.RemoveTenderAmountOfStoreCurrency

instance.RemoveTenderAmountOfStoreCurrency = value
```

``` csharp
[ColumnAttribute("REMOVETENDERAMOUNT")]
[DataMemberAttribute]
public decimal RemoveTenderAmountOfStoreCurrency { get; set; }
```

``` c++
[ColumnAttribute(L"REMOVETENDERAMOUNT")]
[DataMemberAttribute]
public:
property Decimal RemoveTenderAmountOfStoreCurrency {
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

