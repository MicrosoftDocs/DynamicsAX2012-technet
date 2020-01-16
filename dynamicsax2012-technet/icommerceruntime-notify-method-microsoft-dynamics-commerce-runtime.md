---
title: ICommerceRuntime.Notify Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: Notify Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.Notify(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.icommerceruntime.notify(v=AX.60)
ms:contentKeyID: 65321157
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ICommerceRuntime.Notify
dev_langs:
- CSharp
- C++
- VB
---

# Notify Method

Notifies the specified context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Function Notify ( _
    context As RequestContext, _
    notification As Notification _
) As Boolean
'Usage
Dim instance As ICommerceRuntime
Dim context As RequestContext
Dim notification As Notification
Dim returnValue As Boolean

returnValue = instance.Notify(context, _
    notification)
```

``` csharp
bool Notify(
    RequestContext context,
    Notification notification
)
```

``` c++
bool Notify(
    RequestContext^ context, 
    Notification^ notification
)
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

## See Also

#### Reference

[ICommerceRuntime Interface](icommerceruntime-interface-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

