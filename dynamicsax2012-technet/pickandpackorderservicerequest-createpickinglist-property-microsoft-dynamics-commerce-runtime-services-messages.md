---
title: PickAndPackOrderServiceRequest.CreatePickingList Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreatePickingList Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.CreatePickingList
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.pickandpackorderservicerequest.createpickinglist(v=AX.60)
ms:contentKeyID: 62208876
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.CreatePickingList
dev_langs:
- CSharp
- C++
- VB
---

# CreatePickingList Property

Gets a value indicating whether the creation of a picking list should be performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CreatePickingList As Boolean
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderServiceRequest
Dim value As Boolean

value = instance.CreatePickingList
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public bool CreatePickingList { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property bool CreatePickingList {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PickAndPackOrderServiceRequest Class](pickandpackorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

