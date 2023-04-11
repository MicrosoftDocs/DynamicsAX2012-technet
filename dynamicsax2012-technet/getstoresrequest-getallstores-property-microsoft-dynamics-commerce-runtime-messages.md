---
title: GetStoresRequest.GetAllStores Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetAllStores Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresRequest.GetAllStores
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoresrequest.getallstores(v=AX.60)
ms:contentKeyID: 62213281
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresRequest.GetAllStores
dev_langs:
- CSharp
- C++
- VB
---

# GetAllStores Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether this request the retrieval of all stores or a subset of them.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property GetAllStores As Boolean
    Get
'Usage
Dim instance As GetStoresRequest
Dim value As Boolean

value = instance.GetAllStores
```

``` csharp
[IgnoreDataMemberAttribute]
public bool GetAllStores { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property bool GetAllStores {
    bool get ();
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetStoresRequest Class](getstoresrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

