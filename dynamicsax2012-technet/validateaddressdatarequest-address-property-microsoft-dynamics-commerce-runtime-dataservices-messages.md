---
title: ValidateAddressDataRequest.Address Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: Address Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataRequest.Address
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.validateaddressdatarequest.address(v=AX.60)
ms:contentKeyID: 65319993
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ValidateAddressDataRequest.Address
dev_langs:
- CSharp
- C++
- VB
---

# Address Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Address As Address
    Get
    Private Set
'Usage
Dim instance As ValidateAddressDataRequest
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

[ValidateAddressDataRequest Class](validateaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

