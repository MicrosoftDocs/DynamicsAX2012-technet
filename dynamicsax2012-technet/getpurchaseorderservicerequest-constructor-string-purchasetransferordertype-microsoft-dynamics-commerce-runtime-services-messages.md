---
title: GetPurchaseOrderServiceRequest Constructor (String, PurchaseTransferOrderType) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetPurchaseOrderServiceRequest Constructor (String, PurchaseTransferOrderType)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpurchaseorderservicerequest.getpurchaseorderservicerequest(v=AX.60)
ms:contentKeyID: 65321286
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetPurchaseOrderServiceRequest Constructor (String, PurchaseTransferOrderType)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    orderId As String, _
    orderType As PurchaseTransferOrderType _
)
'Usage
Dim orderId As String
Dim orderType As PurchaseTransferOrderType

Dim instance As New GetPurchaseOrderServiceRequest(orderId, _
    orderType)
```

``` csharp
public GetPurchaseOrderServiceRequest(
    string orderId,
    PurchaseTransferOrderType orderType
)
```

``` c++
public:
GetPurchaseOrderServiceRequest(
    String^ orderId, 
    PurchaseTransferOrderType orderType
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetPurchaseOrderServiceRequest Class](getpurchaseorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetPurchaseOrderServiceRequest Overload](getpurchaseorderservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

