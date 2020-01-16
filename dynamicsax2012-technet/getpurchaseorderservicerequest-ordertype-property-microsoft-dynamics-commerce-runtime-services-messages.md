---
title: GetPurchaseOrderServiceRequest.OrderType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceRequest.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpurchaseorderservicerequest.ordertype(v=AX.60)
ms:contentKeyID: 62210647
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceRequest.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property

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
Dim instance As GetPurchaseOrderServiceRequest
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

[GetPurchaseOrderServiceRequest Class](getpurchaseorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

