---
title: HaltNotificationHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.Notifications)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Notifications.HaltNotificationHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notifications.haltnotificationhandler.execute(v=AX.60)
ms:contentKeyID: 65315508
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Notifications.HaltNotificationHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Notifications](microsoft-dynamics-commerce-runtime-notifications-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    notification As Notification _
) As Boolean
'Usage
Dim instance As HaltNotificationHandler
Dim notification As Notification
Dim returnValue As Boolean

returnValue = instance.Execute(notification)
```

``` csharp
public bool Execute(
    Notification notification
)
```

``` c++
public:
virtual bool Execute(
    Notification^ notification
) sealed
```

#### Parameters

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

#### Implements

[INotificationHandler.Execute(Notification)](inotificationhandler-execute-method-microsoft-dynamics-commerce-runtime-notifications.md)  

## See Also

#### Reference

[HaltNotificationHandler Class](haltnotificationhandler-class-microsoft-dynamics-commerce-runtime-notifications.md)

[Microsoft.Dynamics.Commerce.Runtime.Notifications Namespace](microsoft-dynamics-commerce-runtime-notifications-namespace.md)

