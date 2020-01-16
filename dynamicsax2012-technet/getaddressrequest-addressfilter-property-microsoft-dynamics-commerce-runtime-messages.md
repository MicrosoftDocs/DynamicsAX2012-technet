---
title: GetAddressRequest.AddressFilter Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AddressFilter Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.AddressFilter
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressrequest.addressfilter(v=AX.60)
ms:contentKeyID: 62209889
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.AddressFilter
dev_langs:
- CSharp
- C++
- VB
---

# AddressFilter Property

Gets or sets the address filter.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressFilter As AddressFilter
    Get
    Set
'Usage
Dim instance As GetAddressRequest
Dim value As AddressFilter

value = instance.AddressFilter

instance.AddressFilter = value
```

``` csharp
[DataMemberAttribute]
public AddressFilter AddressFilter { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property AddressFilter AddressFilter {
    AddressFilter get ();
    void set (AddressFilter value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFilter](addressfilter-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [AddressFilter](addressfilter-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[GetAddressRequest Class](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

