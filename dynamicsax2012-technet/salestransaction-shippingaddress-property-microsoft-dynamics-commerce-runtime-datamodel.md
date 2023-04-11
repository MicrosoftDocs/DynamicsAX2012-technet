---
title: SalesTransaction.ShippingAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ShippingAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.shippingaddress(v=AX.60)
ms:contentKeyID: 49826747
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.ShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# ShippingAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

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
Dim instance As SalesTransaction
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
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

