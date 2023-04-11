---
title: GetAddressesDataRequest.AddressRecordIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: AddressRecordIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressesDataRequest.AddressRecordIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressesdatarequest.addressrecordids(v=AX.60)
ms:contentKeyID: 65316164
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressesDataRequest.AddressRecordIds
dev_langs:
- CSharp
- C++
- VB
---

# AddressRecordIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of address record identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AddressRecordIds As IEnumerable(Of Long)
    Get
    Private Set
'Usage
Dim instance As GetAddressesDataRequest
Dim value As IEnumerable(Of Long)

value = instance.AddressRecordIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<long> AddressRecordIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<long long>^ AddressRecordIds {
    IEnumerable<long long>^ get ();
    private: void set (IEnumerable<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
The collection of address record identifiers.  

## See Also

#### Reference

[GetAddressesDataRequest Class](getaddressesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

