---
title: Address.AddressType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.AddressType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.addresstype(v=AX.60)
ms:contentKeyID: 62207656
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.AddressType
dev_langs:
- CSharp
- C++
- VB
---

# AddressType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Address Type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("ADDRESSTYPE")> _
Public Property AddressType As AddressType
    Get
    Set
'Usage
Dim instance As Address
Dim value As AddressType

value = instance.AddressType

instance.AddressType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("ADDRESSTYPE")]
public AddressType AddressType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"ADDRESSTYPE")]
public:
property AddressType AddressType {
    AddressType get ();
    void set (AddressType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressType](addresstype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AddressType](addresstype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

