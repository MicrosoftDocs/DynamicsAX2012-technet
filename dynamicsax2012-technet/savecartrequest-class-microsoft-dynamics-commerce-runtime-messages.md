---
title: SaveCartRequest Class (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SaveCartRequest Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.savecartrequest(v=AX.60)
ms:contentKeyID: 62208939
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest
dev_langs:
- CSharp
- C++
- VB
---

# SaveCartRequest Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Updates item quantities on the given shopping cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<KnownTypeAttribute(GetType(Address))> _
<DataContractAttribute> _
Public Class SaveCartRequest _
    Inherits Request
'Usage
Dim instance As SaveCartRequest
```

``` csharp
[KnownTypeAttribute(typeof(Address))]
[DataContractAttribute]
public class SaveCartRequest : Request
```

``` c++
[KnownTypeAttribute(typeof(Address))]
[DataContractAttribute]
public ref class SaveCartRequest : public Request
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartRequest  
      [Microsoft.Dynamics.Commerce.Runtime.Messages.SaveCartLinesRequest](savecartlinesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

