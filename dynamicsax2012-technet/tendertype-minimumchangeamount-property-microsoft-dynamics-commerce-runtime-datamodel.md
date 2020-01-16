---
title: TenderType.MinimumChangeAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MinimumChangeAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumChangeAmount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tendertype.minimumchangeamount(v=AX.60)
ms:contentKeyID: 62211332
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TenderType.MinimumChangeAmount
dev_langs:
- CSharp
- C++
- VB
---

# MinimumChangeAmount Property

Gets or sets the minimum change amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MINIMUMCHANGEAMOUNT")> _
<DataMemberAttribute> _
Public Property MinimumChangeAmount As Decimal
    Get
    Set
'Usage
Dim instance As TenderType
Dim value As Decimal

value = instance.MinimumChangeAmount

instance.MinimumChangeAmount = value
```

``` csharp
[ColumnAttribute("MINIMUMCHANGEAMOUNT")]
[DataMemberAttribute]
public decimal MinimumChangeAmount { get; set; }
```

``` c++
[ColumnAttribute(L"MINIMUMCHANGEAMOUNT")]
[DataMemberAttribute]
public:
property Decimal MinimumChangeAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TenderType Class](tendertype-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

