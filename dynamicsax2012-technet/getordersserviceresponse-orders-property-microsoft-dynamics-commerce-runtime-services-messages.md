---
title: GetOrdersServiceResponse.Orders Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Orders Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceResponse.Orders
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getordersserviceresponse.orders(v=AX.60)
ms:contentKeyID: 49843534
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetOrdersServiceResponse.Orders
dev_langs:
- CSharp
- C++
- VB
---

# Orders Property

Gets the collection of orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Orders As ReadOnlyCollection(Of SalesOrder)
    Get
    Private Set
'Usage
Dim instance As GetOrdersServiceResponse
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
Returns [Collection\<T\>](https://technet.microsoft.com/library/ms132397\(v=ax.60\)).  

## See Also

#### Reference

[GetOrdersServiceResponse Class](getordersserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

