---
title: StockCountJournal Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StockCountJournal Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.stockcountjournal(v=AX.60)
ms:contentKeyID: 62214435
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal
dev_langs:
- CSharp
- C++
- VB
---

# StockCountJournal Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

StockCountJournal entity class, it contains the properties mapped to RetailStockCountJournal table in RetailServer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "JOURNALID", IsDescending := True)> _
<DataContractAttribute> _
Public Class StockCountJournal _
    Inherits CommerceEntity
'Usage
Dim instance As StockCountJournal
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "JOURNALID", IsDescending = true)]
[DataContractAttribute]
public class StockCountJournal : CommerceEntity
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"JOURNALID", IsDescending = true)]
[DataContractAttribute]
public ref class StockCountJournal : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.StockCountJournal  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

