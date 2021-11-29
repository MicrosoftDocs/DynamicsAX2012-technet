---
title: SavePurchaseOrderServiceRequest Constructor (Boolean, PurchaseOrder) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SavePurchaseOrderServiceRequest Constructor (Boolean, PurchaseOrder)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePurchaseOrderServiceRequest.#ctor(System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savepurchaseorderservicerequest.savepurchaseorderservicerequest(v=AX.60)
ms:contentKeyID: 65315535
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SavePurchaseOrderServiceRequest Constructor (Boolean, PurchaseOrder)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    commit As Boolean, _
    purchaseOrder As PurchaseOrder _
)
'Usage
Dim commit As Boolean
Dim purchaseOrder As PurchaseOrder

Dim instance As New SavePurchaseOrderServiceRequest(commit, _
    purchaseOrder)
```

``` csharp
public SavePurchaseOrderServiceRequest(
    bool commit,
    PurchaseOrder purchaseOrder
)
```

``` c++
public:
SavePurchaseOrderServiceRequest(
    bool commit, 
    PurchaseOrder^ purchaseOrder
)
```

#### Parameters

  - commit  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - purchaseOrder  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SavePurchaseOrderServiceRequest Class](savepurchaseorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[SavePurchaseOrderServiceRequest Overload](savepurchaseorderservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

