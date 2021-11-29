---
title: SalesTransactionDataManager.GetTransactionById Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTransactionById Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetTransactionById(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.gettransactionbyid(v=AX.60)
ms:contentKeyID: 62202000
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetTransactionById
dev_langs:
- CSharp
- C++
- VB
---

# GetTransactionById Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales transaction by identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransactionById ( _
    transactionId As String, _
    columnSet As ColumnSet _
) As SalesTransaction
'Usage
Dim instance As SalesTransactionDataManager
Dim transactionId As String
Dim columnSet As ColumnSet
Dim returnValue As SalesTransaction

returnValue = instance.GetTransactionById(transactionId, _
    columnSet)
```

``` csharp
public SalesTransaction GetTransactionById(
    string transactionId,
    ColumnSet columnSet
)
```

``` c++
public:
SalesTransaction^ GetTransactionById(
    String^ transactionId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - transactionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The sales transaction.  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

