---
title: CreateStockCountJournalRealtimeRequest.Description Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Description Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalRealtimeRequest.Description
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.createstockcountjournalrealtimerequest.description(v=AX.60)
ms:contentKeyID: 65317474
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CreateStockCountJournalRealtimeRequest.Description
dev_langs:
- CSharp
- C++
- VB
---

# Description Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Description As String
    Get
    Private Set
'Usage
Dim instance As CreateStockCountJournalRealtimeRequest
Dim value As String

value = instance.Description
```

``` csharp
[DataMemberAttribute]
public string Description { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Description {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CreateStockCountJournalRealtimeRequest Class](createstockcountjournalrealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

