---
title: INotificationHandler.Execute Method  (Microsoft.Dynamics.Commerce.Runtime.Notifications)
TOCTitle: Execute Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Notifications.INotificationHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notifications.inotificationhandler.execute(v=AX.60)
ms:contentKeyID: 49856612
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Notifications.INotificationHandler.Execute
dev_langs:
- CSharp
- C++
- VB
---

# Execute Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Executes the logic within the specified context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Notifications](microsoft-dynamics-commerce-runtime-notifications-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function Execute ( _
    notification As Notification _
) As Boolean
'Usage
Dim instance As INotificationHandler
Dim notification As Notification
Dim returnValue As Boolean

returnValue = instance.Execute(notification)
```

``` csharp
bool Execute(
    Notification notification
)
```

``` c++
bool Execute(
    Notification^ notification
)
```

#### Parameters

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Action to take by the client code. True if error is critical and executed needs to stopFalse otherwise.  

## See Also

#### Reference

[INotificationHandler Interface](inotificationhandler-interface-microsoft-dynamics-commerce-runtime-notifications.md)

[Microsoft.Dynamics.Commerce.Runtime.Notifications Namespace](microsoft-dynamics-commerce-runtime-notifications-namespace.md)

