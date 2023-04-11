---
title: GetStockCountRequest.IncludeOnlyTransactions Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IncludeOnlyTransactions Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStockCountRequest.IncludeOnlyTransactions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstockcountrequest.includeonlytransactions(v=AX.60)
ms:contentKeyID: 62212878
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStockCountRequest.IncludeOnlyTransactions
dev_langs:
- CSharp
- C++
- VB
---

# IncludeOnlyTransactions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to retrieve only transactions; otherwise, journals are included as well.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IncludeOnlyTransactions As Boolean
    Get
    Set
'Usage
Dim instance As GetStockCountRequest
Dim value As Boolean

value = instance.IncludeOnlyTransactions

instance.IncludeOnlyTransactions = value
```

``` csharp
[DataMemberAttribute]
public bool IncludeOnlyTransactions { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IncludeOnlyTransactions {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetStockCountRequest Class](getstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

