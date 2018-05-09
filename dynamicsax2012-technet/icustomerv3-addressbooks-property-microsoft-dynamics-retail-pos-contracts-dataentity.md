---
title: ICustomerV3.AddressBooks Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: AddressBooks Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV3.AddressBooks
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.dataentity.icustomerv3.addressbooks(v=AX.60)
ms:contentKeyID: 62202351
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerV3.AddressBooks
dev_langs:
- CSharp
- C++
- VB
---

# AddressBooks Property

Gets or sets the address books.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property AddressBooks As ICollection(Of IAddressBookPartyData)
    Get
    Set
'Usage
Dim instance As ICustomerV3
Dim value As ICollection(Of IAddressBookPartyData)

value = instance.AddressBooks

instance.AddressBooks = value
```

``` csharp
ICollection<IAddressBookPartyData> AddressBooks { get; set; }
```

``` c++
property ICollection<IAddressBookPartyData^>^ AddressBooks {
    ICollection<IAddressBookPartyData^>^ get ();
    void set (ICollection<IAddressBookPartyData^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[IAddressBookPartyData](iaddressbookpartydata-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
The address books.  

## See Also

#### Reference

[ICustomerV3 Interface](icustomerv3-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

