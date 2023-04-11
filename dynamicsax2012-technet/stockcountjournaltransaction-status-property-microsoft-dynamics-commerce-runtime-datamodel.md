---
title: StockCountJournalTransaction.Status Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Status Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.Status
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.status(v=AX.60)
ms:contentKeyID: 62203717
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.Status
dev_langs:
- CSharp
- C++
- VB
---

# Status Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STATUS")> _
<DataMemberAttribute> _
Public Property Status As Integer
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As Integer

value = instance.Status

instance.Status = value
```

``` csharp
[ColumnAttribute("STATUS")]
[DataMemberAttribute]
public int Status { get; set; }
```

``` c++
[ColumnAttribute(L"STATUS")]
[DataMemberAttribute]
public:
property int Status {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

