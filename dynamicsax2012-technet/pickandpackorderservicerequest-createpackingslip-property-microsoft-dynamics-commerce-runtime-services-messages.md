---
title: PickAndPackOrderServiceRequest.CreatePackingSlip Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CreatePackingSlip Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.CreatePackingSlip
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.pickandpackorderservicerequest.createpackingslip(v=AX.60)
ms:contentKeyID: 62209566
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.CreatePackingSlip
dev_langs:
- CSharp
- C++
- VB
---

# CreatePackingSlip Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the creation of a packing slip should be performed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property CreatePackingSlip As Boolean
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderServiceRequest
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

[PickAndPackOrderServiceRequest Class](pickandpackorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

