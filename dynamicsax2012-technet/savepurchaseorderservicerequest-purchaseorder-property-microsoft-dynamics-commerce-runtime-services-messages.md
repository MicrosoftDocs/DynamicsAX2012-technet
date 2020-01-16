---
title: SavePurchaseOrderServiceRequest.PurchaseOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PurchaseOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePurchaseOrderServiceRequest.PurchaseOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.savepurchaseorderservicerequest.purchaseorder(v=AX.60)
ms:contentKeyID: 62208607
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.SavePurchaseOrderServiceRequest.PurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseOrder Property

Gets or sets the purchase order to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PurchaseOrder As PurchaseOrder
    Get
    Set
'Usage
Dim instance As SavePurchaseOrderServiceRequest
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

[SavePurchaseOrderServiceRequest Class](savepurchaseorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

