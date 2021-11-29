---
title: StockCountJournal.CreateDataRow Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CreateDataRow Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal.CreateDataRow(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournal.createdatarow(v=AX.60)
ms:contentKeyID: 65322781
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal.CreateDataRow
dev_langs:
- CSharp
- C++
- VB
---

# CreateDataRow Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function CreateDataRow ( _
    table As DataTable _
) As DataRow
'Usage
Dim instance As StockCountJournal
Dim table As DataTable
Dim returnValue As DataRow

returnValue = instance.CreateDataRow(table)
```

``` csharp
public DataRow CreateDataRow(
    DataTable table
)
```

``` c++
public:
DataRow^ CreateDataRow(
    DataTable^ table
)
```

#### Parameters

  - table  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[StockCountJournal Class](stockcountjournal-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

