---
title: PickAndPackOrderServiceRequest.InventoryLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: InventoryLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.InventoryLocationId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.pickandpackorderservicerequest.inventorylocationid(v=AX.60)
ms:contentKeyID: 62207300
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.InventoryLocationId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryLocationId Property

Gets the inventory location identifier where the operation is taking place.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<RequiredAttribute> _
<DataMemberAttribute> _
Public Property InventoryLocationId As String
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderServiceRequest
Dim value As String

value = instance.InventoryLocationId
```

``` csharp
[RequiredAttribute]
[DataMemberAttribute]
public string InventoryLocationId { get; private set; }
```

``` c++
[RequiredAttribute]
[DataMemberAttribute]
public:
property String^ InventoryLocationId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PickAndPackOrderServiceRequest Class](pickandpackorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

