---
title: IAddressV1.AddressType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AddressType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.AddressType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressv1.addresstype(v=AX.60)
ms:contentKeyID: 47128196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressV1.AddressType
dev_langs:
- CSharp
- C++
- VB
---

# AddressType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of address.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AddressType As AddressType
    Get
    Set
'Usage
Dim instance As IAddressV1
Dim value As AddressType

value = instance.AddressType

instance.AddressType = value
```

``` csharp
AddressType AddressType { get; set; }
```

``` c++
property AddressType AddressType {
    AddressType get ();
    void set (AddressType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.AddressType](addresstype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.AddressType](addresstype-enumeration-microsoft-dynamics-retail-pos-contracts-dataentity.md) value.  

## See Also

#### Reference

[IAddressV1 Interface](iaddressv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

