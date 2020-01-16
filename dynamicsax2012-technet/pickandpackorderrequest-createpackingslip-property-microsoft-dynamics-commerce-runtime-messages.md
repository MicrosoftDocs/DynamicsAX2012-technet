---
title: PickAndPackOrderRequest.CreatePackingSlip Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CreatePackingSlip Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.CreatePackingSlip
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pickandpackorderrequest.createpackingslip(v=AX.60)
ms:contentKeyID: 62210511
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.CreatePackingSlip
dev_langs:
- CSharp
- C++
- VB
---

# CreatePackingSlip Property

Gets a value indicating whether the creation of a packing slip should be performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CreatePackingSlip As Boolean
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderRequest
Dim value As Boolean

value = instance.CreatePackingSlip
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public bool CreatePackingSlip { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property bool CreatePackingSlip {
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

