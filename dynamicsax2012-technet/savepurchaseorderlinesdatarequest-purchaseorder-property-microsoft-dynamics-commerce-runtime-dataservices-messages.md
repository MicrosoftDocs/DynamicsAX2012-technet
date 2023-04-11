---
title: SavePurchaseOrderLinesDataRequest.PurchaseOrder Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PurchaseOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SavePurchaseOrderLinesDataRequest.PurchaseOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.savepurchaseorderlinesdatarequest.purchaseorder(v=AX.60)
ms:contentKeyID: 65323185
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SavePurchaseOrderLinesDataRequest.PurchaseOrder
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the purchase order to be saved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PurchaseOrder As PurchaseOrder
    Get
    Private Set
'Usage
Dim instance As SavePurchaseOrderLinesDataRequest
Dim value As PurchaseOrder

value = instance.PurchaseOrder
```

``` csharp
[DataMemberAttribute]
public PurchaseOrder PurchaseOrder { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property PurchaseOrder^ PurchaseOrder {
    PurchaseOrder^ get ();
    private: void set (PurchaseOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SavePurchaseOrderLinesDataRequest Class](savepurchaseorderlinesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

