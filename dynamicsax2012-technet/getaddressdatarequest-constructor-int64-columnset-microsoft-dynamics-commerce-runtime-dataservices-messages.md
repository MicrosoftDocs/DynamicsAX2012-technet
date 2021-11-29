---
title: GetAddressDataRequest Constructor (Int64, ColumnSet) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetAddressDataRequest Constructor (Int64, ColumnSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest.#ctor(System.Int64,Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressdatarequest.getaddressdatarequest(v=AX.60)
ms:contentKeyID: 65322946
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressDataRequest Constructor (Int64, ColumnSet)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetAddressDataRequest](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    addressRecordId As Long, _
    columnSet As ColumnSet _
)
'Usage
Dim addressRecordId As Long
Dim columnSet As ColumnSet

Dim instance As New GetAddressDataRequest(addressRecordId, _
    columnSet)
```

``` csharp
public GetAddressDataRequest(
    long addressRecordId,
    ColumnSet columnSet
)
```

``` c++
public:
GetAddressDataRequest(
    long long addressRecordId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - addressRecordId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[GetAddressDataRequest Class](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetAddressDataRequest Overload](getaddressdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

