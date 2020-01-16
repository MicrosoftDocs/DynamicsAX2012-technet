---
title: DeleteStockCountRequest.JournalId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: JournalId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.JournalId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletestockcountrequest.journalid(v=AX.60)
ms:contentKeyID: 62214241
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.JournalId
dev_langs:
- CSharp
- C++
- VB
---

# JournalId Property

Gets the JournalId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property JournalId As String
    Get
    Private Set
'Usage
Dim instance As DeleteStockCountRequest
Dim value As String

value = instance.JournalId
```

``` csharp
[DataMemberAttribute]
public string JournalId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ JournalId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[DeleteStockCountRequest Class](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

