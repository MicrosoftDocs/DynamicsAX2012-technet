---
title: CommerceRuntime.Notify Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Notify Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.Notify(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.notify(v=AX.60)
ms:contentKeyID: 49844928
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.Notify
dev_langs:
- CSharp
- C++
- VB
---

# Notify Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Notifies the specified context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function Notify ( _
    context As RequestContext, _
    notification As Notification _
) As Boolean
'Usage
Dim instance As CommerceRuntime
Dim context As RequestContext
Dim notification As Notification
Dim returnValue As Boolean

returnValue = instance.Notify(context, _
    notification)
```

``` csharp
public bool Notify(
    RequestContext context,
    Notification notification
)
```

``` c++
public:
virtual bool Notify(
    RequestContext^ context, 
    Notification^ notification
) sealed
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - notification  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether the operation should stop.  

#### Implements

[ICommerceRuntime.Notify(RequestContext, Notification)](icommerceruntime-notify-method-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

