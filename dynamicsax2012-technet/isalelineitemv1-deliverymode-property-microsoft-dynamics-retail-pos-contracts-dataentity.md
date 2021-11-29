---
title: ISaleLineItemV1.DeliveryMode Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: DeliveryMode Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DeliveryMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isalelineitemv1.deliverymode(v=AX.60)
ms:contentKeyID: 49819183
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItemV1.DeliveryMode
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the delivery mode.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property DeliveryMode As IDeliveryMode
    Get
    Set
'Usage
Dim instance As ISaleLineItemV1
Dim value As IDeliveryMode

value = instance.DeliveryMode

instance.DeliveryMode = value
```

``` csharp
IDeliveryMode DeliveryMode { get; set; }
```

``` c++
property IDeliveryMode^ DeliveryMode {
    IDeliveryMode^ get ();
    void set (IDeliveryMode^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDeliveryMode](ideliverymode-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Returns [IDeliveryMode](ideliverymode-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md).  

## See Also

#### Reference

[ISaleLineItemV1 Interface](isalelineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

