---
title: GetListingAvailableQuantitiesRequest Constructor (QueryResultSettings, IEnumerable(Int64), Int64, String) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetListingAvailableQuantitiesRequest Constructor (QueryResultSettings, IEnumerable(Int64), Int64, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetListingAvailableQuantitiesRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{System.Int64},System.Int64,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getlistingavailablequantitiesrequest.getlistingavailablequantitiesrequest(v=AX.60)
ms:contentKeyID: 65322377
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetListingAvailableQuantitiesRequest Constructor (QueryResultSettings, IEnumerable(Int64), Int64, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    productIds As IEnumerable(Of Long), _
    channelId As Long, _
    customerAccountNumber As String _
)
'Usage
Dim settings As QueryResultSettings
Dim productIds As IEnumerable(Of Long)
Dim channelId As Long
Dim customerAccountNumber As String

Dim instance As New GetListingAvailableQuantitiesRequest(settings, _
    productIds, channelId, customerAccountNumber)
```

``` csharp
public GetListingAvailableQuantitiesRequest(
    QueryResultSettings settings,
    IEnumerable<long> productIds,
    long channelId,
    string customerAccountNumber
)
```

``` c++
public:
GetListingAvailableQuantitiesRequest(
    QueryResultSettings^ settings, 
    IEnumerable<long long>^ productIds, 
    long long channelId, 
    String^ customerAccountNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - productIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetListingAvailableQuantitiesRequest Class](getlistingavailablequantitiesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetListingAvailableQuantitiesRequest Overload](getlistingavailablequantitiesrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

