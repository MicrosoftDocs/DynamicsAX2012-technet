---
title: ShippingRateInfo.ToAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ToAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo.ToAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shippingrateinfo.toaddress(v=AX.60)
ms:contentKeyID: 49835416
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo.ToAddress
dev_langs:
- CSharp
- C++
- VB
---

# ToAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets to address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ToAddress As Address
    Get
    Set
'Usage
Dim instance As ShippingRateInfo
Dim value As Address

value = instance.ToAddress

instance.ToAddress = value
```

``` csharp
[DataMemberAttribute]
public Address ToAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ ToAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
To address.  

## See Also

#### Reference

[ShippingRateInfo Class](shippingrateinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

