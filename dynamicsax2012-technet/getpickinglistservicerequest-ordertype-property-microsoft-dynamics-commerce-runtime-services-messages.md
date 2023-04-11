---
title: GetPickingListServiceRequest.OrderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceRequest.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpickinglistservicerequest.ordertype(v=AX.60)
ms:contentKeyID: 62207061
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPickingListServiceRequest.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type of the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderType As PurchaseTransferOrderType
    Get
    Private Set
'Usage
Dim instance As GetPickingListServiceRequest
Dim value As PurchaseTransferOrderType

value = instance.OrderType
```

``` csharp
[DataMemberAttribute]
public PurchaseTransferOrderType OrderType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PurchaseTransferOrderType OrderType {
    PurchaseTransferOrderType get ();
    private: void set (PurchaseTransferOrderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetPickingListServiceRequest Class](getpickinglistservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

