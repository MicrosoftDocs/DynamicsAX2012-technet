---
title: SalesTransactionDataManager.DeleteTransactions Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: DeleteTransactions Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.DeleteTransactions(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.deletetransactions(v=AX.60)
ms:contentKeyID: 49850704
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.DeleteTransactions
dev_langs:
- CSharp
- C++
- VB
---

# DeleteTransactions Method

Deletes the transactions by their transaction and customer identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub DeleteTransactions ( _
    salesTransactions As IEnumerable(Of SalesTransaction) _
)
'Usage
Dim instance As SalesTransactionDataManager
Dim salesTransactions As IEnumerable(Of SalesTransaction)

instance.DeleteTransactions(salesTransactions)
```

``` csharp
public void DeleteTransactions(
    IEnumerable<SalesTransaction> salesTransactions
)
```

``` c++
public:
void DeleteTransactions(
    IEnumerable<SalesTransaction^>^ salesTransactions
)
```

#### Parameters

  - salesTransactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

