---
title: SyncStockCountRequest.JournalId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: JournalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountRequest.JournalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.syncstockcountrequest.journalid(v=AX.60)
ms:contentKeyID: 62210076
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SyncStockCountRequest.JournalId
dev_langs:
- CSharp
- C++
- VB
---

# JournalId Property

Gets or sets the JournalId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property JournalId As String
    Get
    Set
'Usage
Dim instance As SyncStockCountRequest
Dim value As String

value = instance.JournalId

instance.JournalId = value
```

``` csharp
[DataMemberAttribute]
public string JournalId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ JournalId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SyncStockCountRequest Class](syncstockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

