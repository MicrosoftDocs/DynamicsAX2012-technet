---
title: SalesTransactionDataManager.GetTransactionsByCustomer Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetTransactionsByCustomer Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetTransactionsByCustomer(System.String,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salestransactiondatamanager.gettransactionsbycustomer(v=AX.60)
ms:contentKeyID: 62206349
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesTransactionDataManager.GetTransactionsByCustomer
dev_langs:
- CSharp
- C++
- VB
---

# GetTransactionsByCustomer Method

Gets the transactions by customer account number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetTransactionsByCustomer ( _
    customerId As String, _
    columnSet As ColumnSet _
) As ReadOnlyCollection(Of SalesTransaction)
'Usage
Dim instance As SalesTransactionDataManager
Dim customerId As String
Dim columnSet As ColumnSet
Dim returnValue As ReadOnlyCollection(Of SalesTransaction)

returnValue = instance.GetTransactionsByCustomer(customerId, _
    columnSet)
```

``` csharp
public ReadOnlyCollection<SalesTransaction> GetTransactionsByCustomer(
    string customerId,
    ColumnSet columnSet
)
```

``` c++
public:
ReadOnlyCollection<SalesTransaction^>^ GetTransactionsByCustomer(
    String^ customerId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - customerId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The collection of sales transaction.  

## See Also

#### Reference

[SalesTransactionDataManager Class](salestransactiondatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

