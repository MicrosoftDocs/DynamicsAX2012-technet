---
title: TransferOrder.OrderType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.OrderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorder.ordertype(v=AX.60)
ms:contentKeyID: 62211190
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.OrderType
dev_langs:
- CSharp
- C++
- VB
---

# OrderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the purchase or transfer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property OrderType As PurchaseTransferOrderType
    Get
    Set
'Usage
Dim instance As TransferOrder
Dim value As PurchaseTransferOrderType

value = instance.OrderType

instance.OrderType = value
```

``` csharp
[IgnoreDataMemberAttribute]
public PurchaseTransferOrderType OrderType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
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

[TransferOrder Class](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

