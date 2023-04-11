---
title: CreateShiftRequest.IsShared Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsShared Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest.IsShared
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.createshiftrequest.isshared(v=AX.60)
ms:contentKeyID: 65321877
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateShiftRequest.IsShared
dev_langs:
- CSharp
- C++
- VB
---

# IsShared Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsShared As Boolean
    Get
    Set
'Usage
Dim instance As CreateShiftRequest
Dim value As Boolean

value = instance.IsShared

instance.IsShared = value
```

``` csharp
[DataMemberAttribute]
public bool IsShared { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsShared {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CreateShiftRequest Class](createshiftrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

