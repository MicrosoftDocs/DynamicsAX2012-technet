---
title: SaveStockCountRequest.IsCommitted Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsCommitted Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest.IsCommitted
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savestockcountrequest.iscommitted(v=AX.60)
ms:contentKeyID: 62211334
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveStockCountRequest.IsCommitted
dev_langs:
- CSharp
- C++
- VB
---

# IsCommitted Property

Gets or sets a value indicating whether the data is commited in AX.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCommitted As Boolean
    Get
    Set
'Usage
Dim instance As SaveStockCountRequest
Dim value As Boolean

value = instance.IsCommitted

instance.IsCommitted = value
```

``` csharp
[DataMemberAttribute]
public bool IsCommitted { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCommitted {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SaveStockCountRequest Class](savestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

