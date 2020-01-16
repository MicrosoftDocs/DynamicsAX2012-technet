---
title: OrderWorkflowErrors Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OrderWorkflowErrors Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.OrderWorkflowErrors
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.orderworkflowerrors(v=AX.60)
ms:contentKeyID: 49834313
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.OrderWorkflowErrors
dev_langs:
- CSharp
- C++
- VB
---

# OrderWorkflowErrors Class

Class container for all errors associated with the cart and order workflows.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public NotInheritable Class OrderWorkflowErrors
'Usage
You do not need to declare an instance of a static class in order to access its members.
```

``` csharp
public static class OrderWorkflowErrors
```

``` c++
public ref class OrderWorkflowErrors abstract sealed
```

## Remarks

When adding a new constant, modifying the name of a constant, or deleting a constant, a corresponding change needs to be made in all files below: - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\SharePoint\\StoreFront\\Services\\ServiceResources.resx (StoreFront) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\Framework\\Assets\\Strings\\{locale}\\resources.resjson (mPOS) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\Framework\\Core\\ErrorHelper.ts (mPOS) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\WindowsPhone\\C1\\Pos\\Model\\Exceptions\\DataValidationErrors.cs (Win Phone POS) - %InetRoot%\\Source\\Frameworks\\Retail\\Channels\\Apps\\WindowsPhone\\C1\\Pos\\Application\\Resources\\AppResources.resx (Win Phone POS) so a proper UI message is displayed.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  Microsoft.Dynamics.Commerce.Runtime.Messages.OrderWorkflowErrors  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

