---
title: SavePurchaseOrderRequest.PurchaseOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PurchaseOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.SavePurchaseOrderRequest.PurchaseOrder
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.savepurchaseorderrequest.purchaseorder(v=AX.60)
ms:contentKeyID: 62209971
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.SavePurchaseOrderRequest.PurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseOrder Property

Gets or sets the purchase order to save.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PurchaseOrder As PurchaseOrder
    Get
    Set
'Usage
Dim instance As SavePurchaseOrderRequest
Dim value As PurchaseOrder

value = instance.PurchaseOrder

instance.PurchaseOrder = value
```

``` csharp
[DataMemberAttribute]
public PurchaseOrder PurchaseOrder { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property PurchaseOrder^ PurchaseOrder {
    PurchaseOrder^ get ();
    void set (PurchaseOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SavePurchaseOrderRequest Class](savepurchaseorderrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

