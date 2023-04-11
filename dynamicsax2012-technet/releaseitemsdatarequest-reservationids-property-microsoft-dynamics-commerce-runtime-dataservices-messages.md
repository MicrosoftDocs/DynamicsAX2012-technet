---
title: ReleaseItemsDataRequest.ReservationIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: ReservationIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseItemsDataRequest.ReservationIds
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.releaseitemsdatarequest.reservationids(v=AX.60)
ms:contentKeyID: 65321137
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.ReleaseItemsDataRequest.ReservationIds
dev_langs:
- CSharp
- C++
- VB
---

# ReservationIds Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of reservation identifiers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReservationIds As IEnumerable(Of Guid)
    Get
    Private Set
'Usage
Dim instance As ReleaseItemsDataRequest
Dim value As IEnumerable(Of Guid)

value = instance.ReservationIds
```

``` csharp
[DataMemberAttribute]
public IEnumerable<Guid> ReservationIds { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<Guid>^ ReservationIds {
    IEnumerable<Guid>^ get ();
    private: void set (IEnumerable<Guid>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Guid](https://technet.microsoft.com/library/cey1zx63\(v=ax.60\))\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[ReleaseItemsDataRequest Class](releaseitemsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

