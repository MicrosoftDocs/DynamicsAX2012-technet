---
title: GetTransferOrderRequest.OrderType Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderRequest.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.gettransferorderrequest.ordertype(v=AX.60)
ms:contentKeyID: 62213965
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetTransferOrderRequest.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderType As PurchaseTransferOrderType
    Get
    Set
'Usage
Dim instance As GetTransferOrderRequest
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

[GetTransferOrderRequest Class](gettransferorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

