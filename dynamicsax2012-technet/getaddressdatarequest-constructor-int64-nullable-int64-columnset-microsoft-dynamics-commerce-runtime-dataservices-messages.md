---
title: GetAddressDataRequest Constructor (Int64, Nullable(Int64), ColumnSet) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetAddressDataRequest Constructor (Int64, Nullable(Int64), ColumnSet)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAddressDataRequest.#ctor(System.Int64,System.Nullable{System.Int64},Microsoft.Dynamics.Commerce.Runtime.ColumnSet)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaddressdatarequest.getaddressdatarequest(v=AX.60)
ms:contentKeyID: 65320191
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAddressDataRequest Constructor (Int64, Nullable(Int64), ColumnSet)

Initializes a new instance of the [GetAddressDataRequest](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    addressRecordId As Long, _
    customerRecordId As Nullable(Of Long), _
    columnSet As ColumnSet _
)
'Usage
Dim addressRecordId As Long
Dim customerRecordId As Nullable(Of Long)
Dim columnSet As ColumnSet

Dim instance As New GetAddressDataRequest(addressRecordId, _
    customerRecordId, columnSet)
```

``` csharp
public GetAddressDataRequest(
    long addressRecordId,
    Nullable<long> customerRecordId,
    ColumnSet columnSet
)
```

``` c++
public:
GetAddressDataRequest(
    long long addressRecordId, 
    Nullable<long long> customerRecordId, 
    ColumnSet^ columnSet
)
```

#### Parameters

  - addressRecordId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerRecordId  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - columnSet  
    Type: [Microsoft.Dynamics.Commerce.Runtime.ColumnSet](columnset-class-microsoft-dynamics-commerce-runtime.md)  

## See Also

#### Reference

[GetAddressDataRequest Class](getaddressdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetAddressDataRequest Overload](getaddressdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

