---
title: CartLineData.ShippingAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ShippingAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.shippingaddress(v=AX.60)
ms:contentKeyID: 49832339
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.ShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingAddress Property

Gets or sets the shipping address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SHIPPINGADDRESS")> _
<DataMemberAttribute> _
Public Property ShippingAddress As Address
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As Address

value = instance.ShippingAddress

instance.ShippingAddress = value
```

``` csharp
[ColumnAttribute("SHIPPINGADDRESS")]
[DataMemberAttribute]
public Address ShippingAddress { get; set; }
```

``` c++
[ColumnAttribute(L"SHIPPINGADDRESS")]
[DataMemberAttribute]
public:
property Address^ ShippingAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
The shipping address.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

