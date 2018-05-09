---
title: GetChannelTenderTypesDataRequest Constructor (Int64, Nullable(Int32)) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetChannelTenderTypesDataRequest Constructor (Int64, Nullable(Int32))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetChannelTenderTypesDataRequest.#ctor(System.Int64,System.Nullable{System.Int32})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getchanneltendertypesdatarequest.getchanneltendertypesdatarequest(v=AX.60)
ms:contentKeyID: 65323008
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelTenderTypesDataRequest Constructor (Int64, Nullable(Int32))

Initializes a new instance of the [GetChannelTenderTypesDataRequest](getchanneltendertypesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    countingRequired As Nullable(Of Integer) _
)
'Usage
Dim channelId As Long
Dim countingRequired As Nullable(Of Integer)

Dim instance As New GetChannelTenderTypesDataRequest(channelId, _
    countingRequired)
```

``` csharp
public GetChannelTenderTypesDataRequest(
    long channelId,
    Nullable<int> countingRequired
)
```

``` c++
public:
GetChannelTenderTypesDataRequest(
    long long channelId, 
    Nullable<int> countingRequired
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - countingRequired  
    Type: [System.Nullable](https://technet.microsoft.com/en-us/library/b3h38hb0\(v=ax.60\))\<[Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))\>  

## See Also

#### Reference

[GetChannelTenderTypesDataRequest Class](getchanneltendertypesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetChannelTenderTypesDataRequest Overload](getchanneltendertypesdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

