---
title: TransactionLogDataManager.FillData Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: FillData Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TransactionLogDataManager.FillData(Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog,Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.transactionlogdatamanager.filldata(v=AX.60)
ms:contentKeyID: 65319006
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TransactionLogDataManager.FillData
dev_langs:
- CSharp
- C++
- VB
---

# FillData Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Sub FillData ( _
    transaction As TransactionLog, _
    transactionTable As DataTable _
)
'Usage
Dim transaction As TransactionLog
Dim transactionTable As DataTable

Me.FillData(transaction, transactionTable)
```

``` csharp
protected void FillData(
    TransactionLog transaction,
    DataTable transactionTable
)
```

``` c++
protected:
void FillData(
    TransactionLog^ transaction, 
    DataTable^ transactionTable
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionLog](transactionlog-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - transactionTable  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataTable](datatable-class-microsoft-dynamics-commerce-runtime-data-types.md)  

## See Also

#### Reference

[TransactionLogDataManager Class](transactionlogdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

