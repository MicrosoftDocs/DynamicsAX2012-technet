---
title: NotificationException.Notification Property  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Notification Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.NotificationException.Notification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notificationexception.notification(v=AX.60)
ms:contentKeyID: 62211870
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.NotificationException.Notification
dev_langs:
- CSharp
- C++
- VB
---

# Notification Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the notification that caused the exception.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property Notification As Notification
    Get
    Private Set
'Usage
Dim instance As NotificationException
Dim value As Notification

value = instance.Notification
```

``` csharp
public Notification Notification { get; private set; }
```

``` c++
public:
property Notification^ Notification {
    Notification^ get ();
    private: void set (Notification^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[NotificationException Class](notificationexception-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

