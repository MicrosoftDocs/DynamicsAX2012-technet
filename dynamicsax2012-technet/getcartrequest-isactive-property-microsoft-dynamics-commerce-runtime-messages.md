---
title: GetCartRequest.IsActive Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsActive Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest.IsActive
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getcartrequest.isactive(v=AX.60)
ms:contentKeyID: 62204003
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetCartRequest.IsActive
dev_langs:
- CSharp
- C++
- VB
---

# IsActive Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the parameter that determines if only the most recently used needs to be retrieved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsActive As Boolean
    Get
    Set
'Usage
Dim instance As GetCartRequest
Dim value As Boolean

value = instance.IsActive

instance.IsActive = value
```

``` csharp
[DataMemberAttribute]
public bool IsActive { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsActive {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetCartRequest Class](getcartrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

