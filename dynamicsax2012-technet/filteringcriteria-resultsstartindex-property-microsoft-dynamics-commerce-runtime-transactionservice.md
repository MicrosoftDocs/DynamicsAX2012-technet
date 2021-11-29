---
title: FilteringCriteria.ResultsStartIndex Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: ResultsStartIndex Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.ResultsStartIndex
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.resultsstartindex(v=AX.60)
ms:contentKeyID: 49831067
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.ResultsStartIndex
dev_langs:
- CSharp
- C++
- VB
---

# ResultsStartIndex Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the start index of the results.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property ResultsStartIndex As Integer
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim value As Integer

value = instance.ResultsStartIndex

instance.ResultsStartIndex = value
```

``` csharp
public int ResultsStartIndex { get; set; }
```

``` c++
public:
property int ResultsStartIndex {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The start index of the results.  

## See Also

#### Reference

[FilteringCriteria Class](filteringcriteria-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

