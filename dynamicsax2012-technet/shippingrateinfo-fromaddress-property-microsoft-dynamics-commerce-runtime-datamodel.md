---
title: ShippingRateInfo.FromAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FromAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo.FromAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shippingrateinfo.fromaddress(v=AX.60)
ms:contentKeyID: 49839168
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingRateInfo.FromAddress
dev_langs:
- CSharp
- C++
- VB
---

# FromAddress Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets from address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property FromAddress As Address
    Get
    Set
'Usage
Dim instance As ShippingRateInfo
Dim value As Address

value = instance.FromAddress

instance.FromAddress = value
```

``` csharp
[DataMemberAttribute]
public Address FromAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ FromAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
From address.  

## See Also

#### Reference

[ShippingRateInfo Class](shippingrateinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

