---
title: Address.AddressTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.AddressTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.addresstypevalue(v=AX.60)
ms:contentKeyID: 62202291
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.AddressTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# AddressTypeValue Property

Gets or sets the value of the AddressType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressTypeValue As Integer
    Get
    Set
'Usage
Dim instance As Address
Dim value As Integer

value = instance.AddressTypeValue

instance.AddressTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int AddressTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int AddressTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

