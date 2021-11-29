---
title: PickAndPackOrderRequest Constructor (String, Boolean, Boolean) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PickAndPackOrderRequest Constructor (String, Boolean, Boolean)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.PickAndPackOrderRequest.#ctor(System.String,System.Boolean,System.Boolean)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.pickandpackorderrequest.pickandpackorderrequest(v=AX.60)
ms:contentKeyID: 62204544
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PickAndPackOrderRequest Constructor (String, Boolean, Boolean)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PickAndPackOrderRequest](pickandpackorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesId As String, _
    createPickingList As Boolean, _
    createPackingSlip As Boolean _
)
'Usage
Dim salesId As String
Dim createPickingList As Boolean
Dim createPackingSlip As Boolean

Dim instance As New PickAndPackOrderRequest(salesId, _
    createPickingList, createPackingSlip)
```

``` csharp
public PickAndPackOrderRequest(
    string salesId,
    bool createPickingList,
    bool createPackingSlip
)
```

``` c++
public:
PickAndPackOrderRequest(
    String^ salesId, 
    bool createPickingList, 
    bool createPackingSlip
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

## See Also

#### Reference

[PickAndPackOrderRequest Class](pickandpackorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[PickAndPackOrderRequest Overload](pickandpackorderrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

