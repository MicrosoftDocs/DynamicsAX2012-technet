---
title: FilteringCriteria.EndTime Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: EndTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.EndTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.endtime(v=AX.60)
ms:contentKeyID: 49825798
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.EndTime
dev_langs:
- CSharp
- C++
- VB
---

# EndTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the end time for the query.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property EndTime As DateTime
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim value As DateTime

value = instance.EndTime

instance.EndTime = value
```

``` csharp
public DateTime EndTime { get; set; }
```

``` c++
public:
property DateTime EndTime {
    DateTime get ();
    void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
To end date.  

## Remarks

Regarding serializations: Just use the standard serialization for DateTime won't work for different locales in AX.

We need to use a helper method to manually serialize this into 3 pieces: 1. The AX date string.

2\. The AX time string.

2\. The sequence number for AX date string.

## See Also

#### Reference

[FilteringCriteria Class](filteringcriteria-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

