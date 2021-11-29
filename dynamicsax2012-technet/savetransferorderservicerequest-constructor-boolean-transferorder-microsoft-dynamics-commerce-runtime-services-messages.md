---
title: SaveTransferOrderServiceRequest Constructor (Boolean, TransferOrder) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SaveTransferOrderServiceRequest Constructor (Boolean, TransferOrder)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SaveTransferOrderServiceRequest.#ctor(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savetransferorderservicerequest.savetransferorderservicerequest(v=AX.60)
ms:contentKeyID: 65322670
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SaveTransferOrderServiceRequest Constructor (Boolean, TransferOrder)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commit As Boolean, _
    transferOrder As TransferOrder _
)
'Usage
Dim commit As Boolean
Dim transferOrder As TransferOrder

Dim instance As New SaveTransferOrderServiceRequest(commit, _
    transferOrder)
```

``` csharp
public SaveTransferOrderServiceRequest(
    bool commit,
    TransferOrder transferOrder
)
```

``` c++
public:
SaveTransferOrderServiceRequest(
    bool commit, 
    TransferOrder^ transferOrder
)
```

#### Parameters

  - commit  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - transferOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SaveTransferOrderServiceRequest Class](savetransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[SaveTransferOrderServiceRequest Overload](savetransferorderservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

