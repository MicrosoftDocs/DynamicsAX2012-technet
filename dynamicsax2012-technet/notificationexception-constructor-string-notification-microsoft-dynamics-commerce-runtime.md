---
title: NotificationException Constructor (String, Notification) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NotificationException Constructor (String, Notification)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.NotificationException.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notificationexception.notificationexception(v=AX.60)
ms:contentKeyID: 62211406
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# NotificationException Constructor (String, Notification)

Initializes a new instance of the [NotificationException](notificationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    notification As Notification _
)
'Usage
Dim errorResourceId As String
Dim notification As Notification

Dim instance As New NotificationException(errorResourceId, _
    notification)
```

``` csharp
public NotificationException(
    string errorResourceId,
    Notification notification
)
```

``` c++
public:
NotificationException(
    String^ errorResourceId, 
    Notification^ notification
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[NotificationException Class](notificationexception-class-microsoft-dynamics-commerce-runtime.md)

[NotificationException Overload](notificationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

