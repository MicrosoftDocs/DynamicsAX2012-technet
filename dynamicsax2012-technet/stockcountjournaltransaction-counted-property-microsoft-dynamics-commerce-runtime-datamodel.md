---
title: StockCountJournalTransaction.Counted Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Counted Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.Counted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.counted(v=AX.60)
ms:contentKeyID: 62211267
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.Counted
dev_langs:
- CSharp
- C++
- VB
---

# Counted Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the counted.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTED")> _
Public Property Counted As Decimal
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As Decimal

value = instance.Counted

instance.Counted = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTED")]
public decimal Counted { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTED")]
public:
property Decimal Counted {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

