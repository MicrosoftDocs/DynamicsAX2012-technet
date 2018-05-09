---
title: InvalidShippingAddressNotification.Address Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Address Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidShippingAddressNotification.Address
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.invalidshippingaddressnotification.address(v=AX.60)
ms:contentKeyID: 65320265
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidShippingAddressNotification.Address
dev_langs:
- CSharp
- C++
- VB
---

# Address Property

Gets the invalid address in the context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Address As Address
    Get
    Private Set
'Usage
Dim instance As InvalidShippingAddressNotification
Dim value As Address

value = instance.Address
```

``` csharp
[DataMemberAttribute]
public Address Address { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ Address {
    Address^ get ();
    private: void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[InvalidShippingAddressNotification Class](invalidshippingaddressnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

