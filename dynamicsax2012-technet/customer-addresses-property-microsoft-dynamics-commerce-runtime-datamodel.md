---
title: Customer.Addresses Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Addresses Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Addresses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.addresses(v=AX.60)
ms:contentKeyID: 49853265
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Addresses
dev_langs:
- CSharp
- C++
- VB
---

# Addresses Property

Gets or sets the customer addresses.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Addresses As IList(Of Address)
    Get
    Set
'Usage
Dim instance As Customer
Dim value As IList(Of Address)

value = instance.Addresses

instance.Addresses = value
```

``` csharp
[DataMemberAttribute]
public IList<Address> Addresses { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<Address^>^ Addresses {
    IList<Address^>^ get ();
    void set (IList<Address^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

