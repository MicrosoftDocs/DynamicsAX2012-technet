---
title: CreateOrderFromCartResponse.SalesOrder Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SalesOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartResponse.SalesOrder
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.createorderfromcartresponse.salesorder(v=AX.60)
ms:contentKeyID: 62210695
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CreateOrderFromCartResponse.SalesOrder
dev_langs:
- CSharp
- C++
- VB
---

# SalesOrder Property

Gets the sales order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SalesOrder As SalesOrder
    Get
    Private Set
'Usage
Dim instance As CreateOrderFromCartResponse
Dim value As SalesOrder

value = instance.SalesOrder
```

``` csharp
[DataMemberAttribute]
public SalesOrder SalesOrder { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property SalesOrder^ SalesOrder {
    SalesOrder^ get ();
    private: void set (SalesOrder^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CreateOrderFromCartResponse Class](createorderfromcartresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

