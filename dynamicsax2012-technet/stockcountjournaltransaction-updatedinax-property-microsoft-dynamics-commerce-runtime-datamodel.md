---
title: StockCountJournalTransaction.UpdatedInAx Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UpdatedInAx Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.UpdatedInAx
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.updatedinax(v=AX.60)
ms:contentKeyID: 62211159
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.UpdatedInAx
dev_langs:
- CSharp
- C++
- VB
---

# UpdatedInAx Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the data was updated in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("UPDATEDINAX")> _
<DataMemberAttribute> _
Public Property UpdatedInAx As Boolean
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As Boolean

value = instance.UpdatedInAx

instance.UpdatedInAx = value
```

``` csharp
[ColumnAttribute("UPDATEDINAX")]
[DataMemberAttribute]
public bool UpdatedInAx { get; set; }
```

``` c++
[ColumnAttribute(L"UPDATEDINAX")]
[DataMemberAttribute]
public:
property bool UpdatedInAx {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

