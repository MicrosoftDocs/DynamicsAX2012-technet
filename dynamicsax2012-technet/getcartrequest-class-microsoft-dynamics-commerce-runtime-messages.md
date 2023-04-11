---
title: GetCartRequest Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetCartRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcartrequest(v=AX.60)
ms:contentKeyID: 49855268
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest
dev_langs:
- CSharp
- C++
- VB
---

# GetCartRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the cart specified by cart id.

Optionally creates a new one if the flag to create is set and no cart was found.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class GetCartRequest _
    Inherits Request
'Usage
Dim instance As GetCartRequest
```

``` csharp
[DataContractAttribute]
public class GetCartRequest : Request
```

``` c++
[DataContractAttribute]
public ref class GetCartRequest : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

