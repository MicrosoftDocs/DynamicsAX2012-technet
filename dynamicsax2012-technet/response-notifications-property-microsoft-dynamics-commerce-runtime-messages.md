---
title: Response.Notifications Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Notifications Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.Response.Notifications
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.response.notifications(v=AX.60)
ms:contentKeyID: 49852660
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.Response.Notifications
dev_langs:
- CSharp
- C++
- VB
---

# Notifications Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the notifications.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Notifications As Collection(Of Notification)
    Get
    Private Set
'Usage
Dim instance As Response
Dim value As Collection(Of Notification)

value = instance.Notifications
```

``` csharp
public Collection<Notification> Notifications { get; private set; }
```

``` c++
public:
property Collection<Notification^>^ Notifications {
    Collection<Notification^>^ get ();
    private: void set (Collection<Notification^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.Collection](https://technet.microsoft.com/library/ms132397\(v=ax.60\))\<[Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[Response Class](response-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

