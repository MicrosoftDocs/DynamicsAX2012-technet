---
title: StockCountDataManager.DeleteStockCountJournals Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeleteStockCountJournals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.DeleteStockCountJournals(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.stockcountdatamanager.deletestockcountjournals(v=AX.60)
ms:contentKeyID: 65320480
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.DeleteStockCountJournals
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockCountJournals Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function DeleteStockCountJournals ( _
    journalIds As IEnumerable(Of String) _
) As Integer
'Usage
Dim instance As StockCountDataManager
Dim journalIds As IEnumerable(Of String)
Dim returnValue As Integer

returnValue = instance.DeleteStockCountJournals(journalIds)
```

``` csharp
public int DeleteStockCountJournals(
    IEnumerable<string> journalIds
)
```

``` c++
public:
int DeleteStockCountJournals(
    IEnumerable<String^>^ journalIds
)
```

#### Parameters

  - journalIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[StockCountDataManager Class](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

