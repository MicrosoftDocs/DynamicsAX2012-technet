---
title: NotificationException.Message Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Message Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.NotificationException.Message
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notificationexception.message(v=AX.60)
ms:contentKeyID: 65320257
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.NotificationException.Message
dev_langs:
- CSharp
- C++
- VB
---

# Message Property

This member overrides [Exception.Message](https://technet.microsoft.com/library/9btwf6wk\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Overrides ReadOnly Property Message As String
    Get
'Usage
Dim instance As NotificationException
Dim value As String

value = instance.Message
```

``` csharp
public override string Message { get; }
```

``` c++
public:
virtual property String^ Message {
    String^ get () override;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Implements

[\_Exception.Message](https://technet.microsoft.com/library/b4sz7awd\(v=ax.60\))  

## See Also

#### Reference

[NotificationException Class](notificationexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

