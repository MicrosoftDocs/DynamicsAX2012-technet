---
title: GetCardTypeDataRequest Constructor (Int64, String) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetCardTypeDataRequest Constructor (Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetCardTypeDataRequest.#ctor(System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getcardtypedatarequest.getcardtypedatarequest(v=AX.60)
ms:contentKeyID: 65319563
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetCardTypeDataRequest Constructor (Int64, String)

Initializes a new instance of the [GetCardTypeDataRequest](getcardtypedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    cardTypeId As String _
)
'Usage
Dim channelId As Long
Dim cardTypeId As String

Dim instance As New GetCardTypeDataRequest(channelId, _
    cardTypeId)
```

``` csharp
public GetCardTypeDataRequest(
    long channelId,
    string cardTypeId
)
```

``` c++
public:
GetCardTypeDataRequest(
    long long channelId, 
    String^ cardTypeId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - cardTypeId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetCardTypeDataRequest Class](getcardtypedatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetCardTypeDataRequest Overload](getcardtypedatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

