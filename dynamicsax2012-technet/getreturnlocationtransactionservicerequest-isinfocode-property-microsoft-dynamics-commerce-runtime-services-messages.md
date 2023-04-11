---
title: GetReturnLocationTransactionServiceRequest.IsInfoCode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsInfoCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.IsInfoCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreturnlocationtransactionservicerequest.isinfocode(v=AX.60)
ms:contentKeyID: 65315516
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReturnLocationTransactionServiceRequest.IsInfoCode
dev_langs:
- CSharp
- C++
- VB
---

# IsInfoCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsInfoCode As Boolean
    Get
    Private Set
'Usage
Dim instance As GetReturnLocationTransactionServiceRequest
Dim value As Boolean

value = instance.IsInfoCode
```

``` csharp
[DataMemberAttribute]
public bool IsInfoCode { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsInfoCode {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReturnLocationTransactionServiceRequest Class](getreturnlocationtransactionservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

