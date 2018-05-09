---
title: PickupAtStoreResponse.Order Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Order Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PickupAtStoreResponse.Order
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.pickupatstoreresponse.order(v=AX.60)
ms:contentKeyID: 62210735
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PickupAtStoreResponse.Order
dev_langs:
- CSharp
- C++
- VB
---

# Order Property

Gets the order saved for the pick up operation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property Order As SalesOrder
    Get
    Private Set
'Usage
Dim instance As PickupAtStoreResponse
Dim value As SalesOrder

value = instance.Order
```

``` csharp
public SalesOrder Order { get; private set; }
```

``` c++
public:
property SalesOrder^ Order {
    SalesOrder^ get ();
    private: void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[PickupAtStoreResponse Class](pickupatstoreresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

