---
title: DeleteStockCountRequest Constructor (String, String, String, String, String, String, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: DeleteStockCountRequest Constructor (String, String, String, String, String, String, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.DeleteStockCountRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.deletestockcountrequest.deletestockcountrequest(v=AX.60)
ms:contentKeyID: 62212240
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# DeleteStockCountRequest Constructor (String, String, String, String, String, String, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [DeleteStockCountRequest](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    journalId As String, _
    itemId As String, _
    inventSizeId As String, _
    inventColorId As String, _
    inventStyleId As String, _
    configId As String, _
    isCascadeJournalDelete As Boolean _
)
'Usage
Dim journalId As String
Dim itemId As String
Dim inventSizeId As String
Dim inventColorId As String
Dim inventStyleId As String
Dim configId As String
Dim isCascadeJournalDelete As Boolean

Dim instance As New DeleteStockCountRequest(journalId, _
    itemId, inventSizeId, inventColorId, _
    inventStyleId, configId, isCascadeJournalDelete)
```

``` csharp
public DeleteStockCountRequest(
    string journalId,
    string itemId,
    string inventSizeId,
    string inventColorId,
    string inventStyleId,
    string configId,
    bool isCascadeJournalDelete
)
```

``` c++
public:
DeleteStockCountRequest(
    String^ journalId, 
    String^ itemId, 
    String^ inventSizeId, 
    String^ inventColorId, 
    String^ inventStyleId, 
    String^ configId, 
    bool isCascadeJournalDelete
)
```

#### Parameters

  - journalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventSizeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventColorId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventStyleId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - configId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - isCascadeJournalDelete  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[DeleteStockCountRequest Class](deletestockcountrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[DeleteStockCountRequest Overload](deletestockcountrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

