---
title: ICompositionLoader.GetNotificationHandler Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: GetNotificationHandler Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetNotificationHandler(Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icompositionloader.getnotificationhandler(v=AX.60)
ms:contentKeyID: 65322549
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICompositionLoader.GetNotificationHandler
dev_langs:
- CSharp
- C++
- VB
---

# GetNotificationHandler Method

Gets the notification handler for the specified notification. If no matching handler could be found, the default notification handler (if any) will be returned instead.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function GetNotificationHandler ( _
    notification As Notification _
) As INotificationHandler
'Usage
Dim instance As ICompositionLoader
Dim notification As Notification
Dim returnValue As INotificationHandler

returnValue = instance.GetNotificationHandler(notification)
```

``` csharp
INotificationHandler GetNotificationHandler(
    Notification notification
)
```

``` c++
INotificationHandler^ GetNotificationHandler(
    Notification^ notification
)
```

#### Parameters

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Notifications.INotificationHandler](inotificationhandler-interface-microsoft-dynamics-commerce-runtime-notifications.md)  
A new instance of the notification handler.  

## See Also

#### Reference

[ICompositionLoader Interface](icompositionloader-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

