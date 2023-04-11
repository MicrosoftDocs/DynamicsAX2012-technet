---
title: Cart.OrderNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.OrderNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.ordernumber(v=AX.60)
ms:contentKeyID: 49831397
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.OrderNumber
dev_langs:
- CSharp
- C++
- VB
---

# OrderNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the order number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELREFERENCEID")> _
Public Property OrderNumber As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.OrderNumber

instance.OrderNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELREFERENCEID")]
public string OrderNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELREFERENCEID")]
public:
property String^ OrderNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

This is the channel order number (channel reference id).

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

