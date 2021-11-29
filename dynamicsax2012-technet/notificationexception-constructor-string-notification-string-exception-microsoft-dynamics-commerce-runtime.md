---
title: NotificationException Constructor (String, Notification, String, Exception) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NotificationException Constructor (String, Notification, String, Exception)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.NotificationException.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification,System.String,System.Exception)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notificationexception.notificationexception(v=AX.60)
ms:contentKeyID: 62211208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# NotificationException Constructor (String, Notification, String, Exception)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [NotificationException](notificationexception-class-microsoft-dynamics-commerce-runtime.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    errorResourceId As String, _
    notification As Notification, _
    message As String, _
    inner As Exception _
)
'Usage
Dim errorResourceId As String
Dim notification As Notification
Dim message As String
Dim inner As Exception

Dim instance As New NotificationException(errorResourceId, _
    notification, message, inner)
```

``` csharp
public NotificationException(
    string errorResourceId,
    Notification notification,
    string message,
    Exception inner
)
```

``` c++
public:
NotificationException(
    String^ errorResourceId, 
    Notification^ notification, 
    String^ message, 
    Exception^ inner
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inner  
    Type: [System.Exception](https://technet.microsoft.com/library/c18k6c59\(v=ax.60\))  

## See Also

#### Reference

[NotificationException Class](notificationexception-class-microsoft-dynamics-commerce-runtime.md)

[NotificationException Overload](notificationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

