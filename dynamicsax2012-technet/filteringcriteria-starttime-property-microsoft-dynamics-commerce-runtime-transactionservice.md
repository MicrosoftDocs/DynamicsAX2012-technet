---
title: FilteringCriteria.StartTime Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: StartTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.StartTime
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.starttime(v=AX.60)
ms:contentKeyID: 49856782
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.StartTime
dev_langs:
- CSharp
- C++
- VB
---

# StartTime Property

Gets or sets the start time for the query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property StartTime As DateTime
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim value As DateTime

value = instance.StartTime

instance.StartTime = value
```

``` csharp
public DateTime StartTime { get; set; }
```

``` c++
public:
property DateTime StartTime {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/en-us/library/03ybds8y\(v=ax.60\))  
From date.  

## Remarks

Regarding serializations: Just use the standard serialization for DateTime won't work for different locales in AX.

We need to use a helper method to manually serialize this into 3 pieces: 1. The AX date string.

2\. The AX time string.

2\. The sequence number for AX date string.

## See Also

#### Reference

[FilteringCriteria Class](filteringcriteria-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

