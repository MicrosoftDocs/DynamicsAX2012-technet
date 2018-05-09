---
title: GetTransferOrderServiceRequest Constructor (String, PurchaseTransferOrderType) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetTransferOrderServiceRequest Constructor (String, PurchaseTransferOrderType)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceRequest.#ctor(System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.gettransferorderservicerequest.gettransferorderservicerequest(v=AX.60)
ms:contentKeyID: 65319183
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetTransferOrderServiceRequest Constructor (String, PurchaseTransferOrderType)

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

Dim instance As New GetTransferOrderServiceRequest(orderId, _
    orderType)
```

``` csharp
public GetTransferOrderServiceRequest(
    string orderId,
    PurchaseTransferOrderType orderType
)
```

``` c++
public:
GetTransferOrderServiceRequest(
    String^ orderId, 
    PurchaseTransferOrderType orderType
)
```

#### Parameters

  - orderId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - orderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetTransferOrderServiceRequest Class](gettransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetTransferOrderServiceRequest Overload](gettransferorderservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

