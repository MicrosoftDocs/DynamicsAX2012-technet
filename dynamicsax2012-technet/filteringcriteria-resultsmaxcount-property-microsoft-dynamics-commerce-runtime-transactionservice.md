---
title: FilteringCriteria.ResultsMaxCount Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ResultsMaxCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.ResultsMaxCount
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.resultsmaxcount(v=AX.60)
ms:contentKeyID: 49837926
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.ResultsMaxCount
dev_langs:
- CSharp
- C++
- VB
---

# ResultsMaxCount Property

Gets or sets the max count of the results.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property ResultsMaxCount As Integer
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim value As Integer

value = instance.ResultsMaxCount

instance.ResultsMaxCount = value
```

``` csharp
public int ResultsMaxCount { get; set; }
```

``` c++
public:
property int ResultsMaxCount {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The results max count.  

## See Also

#### Reference

[FilteringCriteria Class](filteringcriteria-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

