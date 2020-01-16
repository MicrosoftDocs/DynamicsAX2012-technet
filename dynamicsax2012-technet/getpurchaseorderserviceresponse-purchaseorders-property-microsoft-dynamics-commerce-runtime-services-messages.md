---
title: GetPurchaseOrderServiceResponse.PurchaseOrders Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: PurchaseOrders Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceResponse.PurchaseOrders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpurchaseorderserviceresponse.purchaseorders(v=AX.60)
ms:contentKeyID: 62211650
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPurchaseOrderServiceResponse.PurchaseOrders
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseOrders Property

Gets the purchase orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property PurchaseOrders As ReadOnlyCollection(Of PurchaseOrder)
    Get
    Private Set
'Usage
Dim instance As GetPurchaseOrderServiceResponse
Dim value As ReadOnlyCollection(Of PurchaseOrder)

value = instance.PurchaseOrders
```

``` csharp
public ReadOnlyCollection<PurchaseOrder> PurchaseOrders { get; private set; }
```

``` c++
public:
property ReadOnlyCollection<PurchaseOrder^>^ PurchaseOrders {
    ReadOnlyCollection<PurchaseOrder^>^ get ();
    private: void set (ReadOnlyCollection<PurchaseOrder^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[PurchaseOrder](purchaseorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetPurchaseOrderServiceResponse Class](getpurchaseorderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

