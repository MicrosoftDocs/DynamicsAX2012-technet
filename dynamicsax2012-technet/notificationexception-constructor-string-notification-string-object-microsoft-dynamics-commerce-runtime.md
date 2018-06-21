---
title: NotificationException Constructor (String, Notification, String, Object ) (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: NotificationException Constructor (String, Notification, String, Object )
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.NotificationException.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification,System.String,System.Object[])
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.notificationexception.notificationexception(v=AX.60)
ms:contentKeyID: 62203793
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# NotificationException Constructor (String, Notification, String, Object )[AX 2012]

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
    ParamArray args As Object() _
)
'Usage
Dim errorResourceId As String
Dim notification As Notification
Dim message As String
Dim args As Object()

Dim instance As New NotificationException(errorResourceId, _
    notification, message, args)
```

``` csharp
public NotificationException(
    string errorResourceId,
    Notification notification,
    string message,
    params Object[] args
)
```

``` c++
public:
NotificationException(
    String^ errorResourceId, 
    Notification^ notification, 
    String^ message, 
    ... array<Object^>^ args
)
```

#### Parameters

  - errorResourceId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - message  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - args  
    Type: [System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))\[\]  

## See Also

#### Reference

[NotificationException Class](notificationexception-class-microsoft-dynamics-commerce-runtime.md)

[NotificationException Overload](notificationexception-constructor-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

