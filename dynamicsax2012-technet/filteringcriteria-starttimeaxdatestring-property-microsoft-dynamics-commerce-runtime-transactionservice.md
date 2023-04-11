---
title: FilteringCriteria.StartTimeAxDateString Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: StartTimeAxDateString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.StartTimeAxDateString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.starttimeaxdatestring(v=AX.60)
ms:contentKeyID: 49852619
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.StartTimeAxDateString
dev_langs:
- CSharp
- C++
- VB
---

# StartTimeAxDateString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the start time as an AX date string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property StartTimeAxDateString As String
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim value As String

value = instance.StartTimeAxDateString

instance.StartTimeAxDateString = value
```

``` csharp
public string StartTimeAxDateString { get; set; }
```

``` c++
public:
property String^ StartTimeAxDateString {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[FilteringCriteria Class](filteringcriteria-class-microsoft-dynamics-commerce-runtime-transactionservice.md)

[Microsoft.Dynamics.Commerce.Runtime.TransactionService Namespace](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)

