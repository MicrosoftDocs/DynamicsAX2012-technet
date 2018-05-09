---
title: StockCountJournalTransaction.InventBatchId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventBatchId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.InventBatchId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.inventbatchid(v=AX.60)
ms:contentKeyID: 62210632
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.InventBatchId
dev_langs:
- CSharp
- C++
- VB
---

# InventBatchId Property

Gets or sets the inventory batch identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTBATCHID")> _
Public Property InventBatchId As String
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As String

value = instance.InventBatchId

instance.InventBatchId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTBATCHID")]
public string InventBatchId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTBATCHID")]
public:
property String^ InventBatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[StockCountJournalTransaction Class](stockcountjournaltransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

