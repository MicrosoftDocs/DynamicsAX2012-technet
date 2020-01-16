---
title: DeleteStockCountRequest.IsCascadeJournalDelete Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsCascadeJournalDelete Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.IsCascadeJournalDelete
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletestockcountrequest.iscascadejournaldelete(v=AX.60)
ms:contentKeyID: 62212156
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.IsCascadeJournalDelete
dev_langs:
- CSharp
- C++
- VB
---

# IsCascadeJournalDelete Property

Gets a value indicating whether the journal should be delete in cascade (or) a particular transaction of an item in a journal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCascadeJournalDelete As Boolean
    Get
    Private Set
'Usage
Dim instance As DeleteStockCountRequest
Dim value As Boolean

value = instance.IsCascadeJournalDelete
```

``` csharp
[DataMemberAttribute]
public bool IsCascadeJournalDelete { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCascadeJournalDelete {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DeleteStockCountRequest Class](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

