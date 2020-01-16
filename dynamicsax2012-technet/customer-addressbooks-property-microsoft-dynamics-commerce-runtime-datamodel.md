---
title: Customer.AddressBooks Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AddressBooks Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.AddressBooks
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.addressbooks(v=AX.60)
ms:contentKeyID: 62210459
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.AddressBooks
dev_langs:
- CSharp
- C++
- VB
---

# AddressBooks Property

Gets or sets the address books for this customer.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property AddressBooks As IList(Of AddressBookPartyData)
    Get
    Set
'Usage
Dim instance As Customer
Dim value As IList(Of AddressBookPartyData)

value = instance.AddressBooks

instance.AddressBooks = value
```

``` csharp
[IgnoreDataMemberAttribute]
public IList<AddressBookPartyData> AddressBooks { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property IList<AddressBookPartyData^>^ AddressBooks {
    IList<AddressBookPartyData^>^ get ();
    void set (IList<AddressBookPartyData^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[AddressBookPartyData](addressbookpartydata-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The address books.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

