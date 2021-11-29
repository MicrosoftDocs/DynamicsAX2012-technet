---
title: GetPurchaseOrderResponse.PurchaseOrders Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: PurchaseOrders Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetPurchaseOrderResponse.PurchaseOrders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getpurchaseorderresponse.purchaseorders(v=AX.60)
ms:contentKeyID: 62202815
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetPurchaseOrderResponse.PurchaseOrders
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseOrders Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of purchase orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PurchaseOrders As ReadOnlyCollection(Of PurchaseOrder)
    Get
    Private Set
'Usage
Dim instance As GetPurchaseOrderResponse
Dim value As ReadOnlyCollection(Of PurchaseOrder)

value = instance.PurchaseOrders
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<PurchaseOrder> PurchaseOrders { get; private set; }
```

``` c++
[DataMemberAttribute]
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

[GetPurchaseOrderResponse Class](getpurchaseorderresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

