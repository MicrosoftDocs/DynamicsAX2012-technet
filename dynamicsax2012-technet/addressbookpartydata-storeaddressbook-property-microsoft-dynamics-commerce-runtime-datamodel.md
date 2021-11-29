---
title: AddressBookPartyData.StoreAddressBook Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StoreAddressBook Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressBookPartyData.StoreAddressBook
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressbookpartydata.storeaddressbook(v=AX.60)
ms:contentKeyID: 62214200
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressBookPartyData.StoreAddressBook
dev_langs:
- CSharp
- C++
- VB
---

# StoreAddressBook Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the store address book.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property StoreAddressBook As Long
    Get
    Set
'Usage
Dim instance As AddressBookPartyData
Dim value As Long

value = instance.StoreAddressBook

instance.StoreAddressBook = value
```

``` csharp
public long StoreAddressBook { get; set; }
```

``` c++
public:
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

[AddressBookPartyData Class](addressbookpartydata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

