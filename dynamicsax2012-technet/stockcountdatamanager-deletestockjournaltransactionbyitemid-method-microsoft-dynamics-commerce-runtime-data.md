---
title: StockCountDataManager.DeleteStockJournalTransactionByItemId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeleteStockJournalTransactionByItemId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.DeleteStockJournalTransactionByItemId(System.String,System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.stockcountdatamanager.deletestockjournaltransactionbyitemid(v=AX.60)
ms:contentKeyID: 62215222
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.StockCountDataManager.DeleteStockJournalTransactionByItemId
dev_langs:
- CSharp
- C++
- VB
---

# DeleteStockJournalTransactionByItemId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Deletes the Stock Count Transactions for the given JournalId and item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function DeleteStockJournalTransactionByItemId ( _
    journalId As String, _
    itemId As String, _
    inventSizeId As String, _
    inventColorId As String, _
    inventStyleId As String, _
    configId As String _
) As Integer
'Usage
Dim instance As StockCountDataManager
Dim journalId As String
Dim itemId As String
Dim inventSizeId As String
Dim inventColorId As String
Dim inventStyleId As String
Dim configId As String
Dim returnValue As Integer

returnValue = instance.DeleteStockJournalTransactionByItemId(journalId, _
    itemId, inventSizeId, inventColorId, _
    inventStyleId, configId)
```

``` csharp
public int DeleteStockJournalTransactionByItemId(
    string journalId,
    string itemId,
    string inventSizeId,
    string inventColorId,
    string inventStyleId,
    string configId
)
```

``` c++
public:
int DeleteStockJournalTransactionByItemId(
    String^ journalId, 
    String^ itemId, 
    String^ inventSizeId, 
    String^ inventColorId, 
    String^ inventStyleId, 
    String^ configId
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventSizeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventColorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventStyleId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - configId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The error code returned from the stored procedure.  

## See Also

#### Reference

[StockCountDataManager Class](stockcountdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

