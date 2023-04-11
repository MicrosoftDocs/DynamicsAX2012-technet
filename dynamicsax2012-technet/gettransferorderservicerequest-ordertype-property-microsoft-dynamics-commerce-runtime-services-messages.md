---
title: GetTransferOrderServiceRequest.OrderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceRequest.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.gettransferorderservicerequest.ordertype(v=AX.60)
ms:contentKeyID: 62210414
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetTransferOrderServiceRequest.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderType As PurchaseTransferOrderType
    Get
    Set
'Usage
Dim instance As GetTransferOrderServiceRequest
Dim value As PurchaseTransferOrderType

value = instance.OrderType

instance.OrderType = value
```

``` csharp
[DataMemberAttribute]
public PurchaseTransferOrderType OrderType { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property PurchaseTransferOrderType OrderType {
    PurchaseTransferOrderType get ();
    void set (PurchaseTransferOrderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PurchaseTransferOrderType](purchasetransferordertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetTransferOrderServiceRequest Class](gettransferorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

