---
title: GetPickingListRequest Constructor (PurchaseTransferOrderType, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetPickingListRequest Constructor (PurchaseTransferOrderType, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetPickingListRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getpickinglistrequest.getpickinglistrequest(v=AX.60)
ms:contentKeyID: 62214488
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetPickingListRequest Constructor (PurchaseTransferOrderType, String)

Initializes a new instance of the [GetPickingListRequest](getpickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    orderType As PurchaseTransferOrderType, _
    orderId As String _
)
'Usage
Dim orderType As PurchaseTransferOrderType
Dim orderId As String

Dim instance As New GetPickingListRequest(orderType, _
    orderId)
```

``` csharp
public GetPickingListRequest(
    PurchaseTransferOrderType orderType,
    string orderId
)
```

``` c++
public:
GetPickingListRequest(
    PurchaseTransferOrderType orderType, 
    String^ orderId
)
```

#### Parameters

  - orderType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - orderId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetPickingListRequest Class](getpickinglistrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetPickingListRequest Overload](getpickinglistrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

