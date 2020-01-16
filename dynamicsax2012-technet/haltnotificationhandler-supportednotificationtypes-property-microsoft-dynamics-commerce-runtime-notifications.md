---
title: HaltNotificationHandler.SupportedNotificationTypes Property  (Microsoft.Dynamics.Commerce.Runtime.Notifications)
TOCTitle: SupportedNotificationTypes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Notifications.HaltNotificationHandler.SupportedNotificationTypes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.notifications.haltnotificationhandler.supportednotificationtypes(v=AX.60)
ms:contentKeyID: 65317934
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Notifications.HaltNotificationHandler.SupportedNotificationTypes
dev_langs:
- CSharp
- C++
- VB
---

# SupportedNotificationTypes Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Notifications](microsoft-dynamics-commerce-runtime-notifications-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services (in Microsoft.Dynamics.Commerce.Runtime.Services.dll)

## Syntax

``` vb
'Declaration
Public ReadOnly Property SupportedNotificationTypes As IEnumerable(Of Type)
    Get
'Usage
Dim instance As HaltNotificationHandler
Dim value As IEnumerable(Of Type)

value = instance.SupportedNotificationTypes
```

``` csharp
public IEnumerable<Type> SupportedNotificationTypes { get; }
```

``` c++
public:
virtual property IEnumerable<Type^>^ SupportedNotificationTypes {
    IEnumerable<Type^>^ get () sealed;
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))\>  

#### Implements

[INotificationHandler.SupportedNotificationTypes](inotificationhandler-supportednotificationtypes-property-microsoft-dynamics-commerce-runtime-notifications.md)  

## See Also

#### Reference

[HaltNotificationHandler Class](haltnotificationhandler-class-microsoft-dynamics-commerce-runtime-notifications.md)

[Microsoft.Dynamics.Commerce.Runtime.Notifications Namespace](microsoft-dynamics-commerce-runtime-notifications-namespace.md)

