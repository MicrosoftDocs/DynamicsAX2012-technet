---
title: PickAndPackOrderRequest.CreatePickingList Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CreatePickingList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.CreatePickingList
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pickandpackorderrequest.createpickinglist(v=AX.60)
ms:contentKeyID: 62209374
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.CreatePickingList
dev_langs:
- CSharp
- C++
- VB
---

# CreatePickingList Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the creation of a picking list should be performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property CreatePickingList As Boolean
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderRequest
Dim value As Boolean

value = instance.CreatePickingList
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public bool CreatePickingList { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property bool CreatePickingList {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PickAndPackOrderRequest Class](pickandpackorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

