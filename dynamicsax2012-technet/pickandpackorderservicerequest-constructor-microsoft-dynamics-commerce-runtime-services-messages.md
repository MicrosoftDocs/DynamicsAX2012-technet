---
title: PickAndPackOrderServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PickAndPackOrderServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.#ctor(System.String,System.Boolean,System.Boolean,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.pickandpackorderservicerequest.pickandpackorderservicerequest(v=AX.60)
ms:contentKeyID: 65322641
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PickAndPackOrderServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesId As String, _
    createPickingList As Boolean, _
    createPackingSlip As Boolean, _
    inventoryLocationId As String _
)
'Usage
Dim salesId As String
Dim createPickingList As Boolean
Dim createPackingSlip As Boolean
Dim inventoryLocationId As String

Dim instance As New PickAndPackOrderServiceRequest(salesId, _
    createPickingList, createPackingSlip, _
    inventoryLocationId)
```

``` csharp
public PickAndPackOrderServiceRequest(
    string salesId,
    bool createPickingList,
    bool createPackingSlip,
    string inventoryLocationId
)
```

``` c++
public:
PickAndPackOrderServiceRequest(
    String^ salesId, 
    bool createPickingList, 
    bool createPackingSlip, 
    String^ inventoryLocationId
)
```

#### Parameters

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - createPickingList  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - createPackingSlip  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - inventoryLocationId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[PickAndPackOrderServiceRequest Class](pickandpackorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

