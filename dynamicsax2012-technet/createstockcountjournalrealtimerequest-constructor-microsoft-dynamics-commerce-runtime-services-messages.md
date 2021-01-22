---
title: CreateStockCountJournalRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreateStockCountJournalRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalRealtimeRequest.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.createstockcountjournalrealtimerequest.createstockcountjournalrealtimerequest(v=AX.60)
ms:contentKeyID: 65321609
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CreateStockCountJournalRealtimeRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    inventoryLocationId As String, _
    description As String _
)
'Usage
Dim inventoryLocationId As String
Dim description As String

Dim instance As New CreateStockCountJournalRealtimeRequest(inventoryLocationId, _
    description)
```

``` csharp
public CreateStockCountJournalRealtimeRequest(
    string inventoryLocationId,
    string description
)
```

``` c++
public:
CreateStockCountJournalRealtimeRequest(
    String^ inventoryLocationId, 
    String^ description
)
```

#### Parameters

  - inventoryLocationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - description  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreateStockCountJournalRealtimeRequest Class](createstockcountjournalrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

