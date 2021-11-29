---
title: IAddressBookPartyDataV1.StoreAddressBook Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: StoreAddressBook Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressBookPartyDataV1.StoreAddressBook
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iaddressbookpartydatav1.storeaddressbook(v=AX.60)
ms:contentKeyID: 62205597
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IAddressBookPartyDataV1.StoreAddressBook
dev_langs:
- CSharp
- C++
- VB
---

# StoreAddressBook Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the store address book.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property StoreAddressBook As Long
    Get
    Set
'Usage
Dim instance As IAddressBookPartyDataV1
Dim value As Long

value = instance.StoreAddressBook

instance.StoreAddressBook = value
```

``` csharp
long StoreAddressBook { get; set; }
```

``` c++
property long long StoreAddressBook {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
The store address book.  

## See Also

#### Reference

[IAddressBookPartyDataV1 Interface](iaddressbookpartydatav1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

