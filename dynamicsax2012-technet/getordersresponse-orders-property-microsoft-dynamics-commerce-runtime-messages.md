---
title: GetOrdersResponse.Orders Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Orders Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersResponse.Orders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getordersresponse.orders(v=AX.60)
ms:contentKeyID: 49849444
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetOrdersResponse.Orders
dev_langs:
- CSharp
- C++
- VB
---

# Orders Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Orders As ReadOnlyCollection(Of SalesOrder)
    Get
    Private Set
'Usage
Dim instance As GetOrdersResponse
Dim value As ReadOnlyCollection(Of SalesOrder)

value = instance.Orders
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<SalesOrder> Orders { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<SalesOrder^>^ Orders {
    ReadOnlyCollection<SalesOrder^>^ get ();
    private: void set (ReadOnlyCollection<SalesOrder^>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[GetOrdersResponse Class](getordersresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

