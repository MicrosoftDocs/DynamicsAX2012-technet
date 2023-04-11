---
title: FilteringCriteria.EndTimeAxTimeString Property  (Microsoft.Dynamics.Commerce.Runtime.TransactionService)
TOCTitle: EndTimeAxTimeString Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.EndTimeAxTimeString
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.transactionservice.filteringcriteria.endtimeaxtimestring(v=AX.60)
ms:contentKeyID: 49821252
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.TransactionService.FilteringCriteria.EndTimeAxTimeString
dev_langs:
- CSharp
- C++
- VB
---

# EndTimeAxTimeString Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the end time as an AX time string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.TransactionService](microsoft-dynamics-commerce-runtime-transactionservice-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.TransactionService (in Microsoft.Dynamics.Commerce.Runtime.TransactionService.dll)

## Syntax

``` vb
'Declaration
Public Property EndTimeAxTimeString As String
    Get
    Set
'Usage
Dim instance As FilteringCriteria
Dim value As String

value = instance.EndTimeAxTimeString

instance.EndTimeAxTimeString = value
```

``` csharp
public string EndTimeAxTimeString { get; set; }
```

``` c++
public:
property String^ EndTimeAxTimeString {
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

