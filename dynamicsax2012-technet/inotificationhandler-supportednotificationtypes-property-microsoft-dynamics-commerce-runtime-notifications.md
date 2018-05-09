---
title: INotificationHandler.SupportedNotificationTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Notifications)
TOCTitle: SupportedNotificationTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Notifications.INotificationHandler.SupportedNotificationTypes
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.notifications.inotificationhandler.supportednotificationtypes(v=AX.60)
ms:contentKeyID: 65321262
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Notifications.INotificationHandler.SupportedNotificationTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedNotificationTypes Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Notifications](microsoft-dynamics-commerce-runtime-notifications-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SupportedNotificationTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As INotificationHandler
Dim value As IEnumerable(Of Type)

value = instance.SupportedNotificationTypes
```

``` csharp
IEnumerable<Type> SupportedNotificationTypes { get; }
```

``` c++
property IEnumerable<Type^>^ SupportedNotificationTypes {
    IEnumerable<Type^>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Type](https://technet.microsoft.com/en-us/library/42892f65\(v=ax.60\))\>  

## See Also

#### Reference

[INotificationHandler Interface](inotificationhandler-interface-microsoft-dynamics-commerce-runtime-notifications.md)

[Microsoft.Dynamics.Commerce.Runtime.Notifications Namespace](microsoft-dynamics-commerce-runtime-notifications-namespace.md)

