---
title: StockCountJournalTransaction.OperationType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OperationType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.OperationType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournaltransaction.operationtype(v=AX.60)
ms:contentKeyID: 62208375
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournalTransaction.OperationType
dev_langs:
- CSharp
- C++
- VB
---

# OperationType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the operation type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPERATIONTYPE")> _
Public Property OperationType As Integer
    Get
    Set
'Usage
Dim instance As StockCountJournalTransaction
Dim value As Integer

value = instance.OperationType

instance.OperationType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPERATIONTYPE")]
public int OperationType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPERATIONTYPE")]
public:
property int OperationType {
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

