---
title: LockCreditMemoRealtimeRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: LockCreditMemoRealtimeRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.LockCreditMemoRealtimeRequest.#ctor(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.lockcreditmemorealtimerequest.lockcreditmemorealtimerequest(v=AX.60)
ms:contentKeyID: 65319837
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.LockCreditMemoRealtimeRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# LockCreditMemoRealtimeRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    memoId As String, _
    storeId As String, _
    terminalId As String _
)
'Usage
Dim memoId As String
Dim storeId As String
Dim terminalId As String

Dim instance As New LockCreditMemoRealtimeRequest(memoId, _
    storeId, terminalId)
```

``` csharp
public LockCreditMemoRealtimeRequest(
    string memoId,
    string storeId,
    string terminalId
)
```

``` c++
public:
LockCreditMemoRealtimeRequest(
    String^ memoId, 
    String^ storeId, 
    String^ terminalId
)
```

#### Parameters

  - memoId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - storeId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[LockCreditMemoRealtimeRequest Class](lockcreditmemorealtimerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

