---
title: GetStoreLocationsRequest Constructor (QueryResultSettings, ICollection(String)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoreLocationsRequest Constructor (QueryResultSettings, ICollection(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoreLocationsRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.ICollection{System.String})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.getstorelocationsrequest.getstorelocationsrequest(v=AX.60)
ms:contentKeyID: 65319819
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoreLocationsRequest Constructor (QueryResultSettings, ICollection(String))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    storeNumbers As ICollection(Of String) _
)
'Usage
Dim settings As QueryResultSettings
Dim storeNumbers As ICollection(Of String)

Dim instance As New GetStoreLocationsRequest(settings, _
    storeNumbers)
```

``` csharp
public GetStoreLocationsRequest(
    QueryResultSettings settings,
    ICollection<string> storeNumbers
)
```

``` c++
public:
GetStoreLocationsRequest(
    QueryResultSettings^ settings, 
    ICollection<String^>^ storeNumbers
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - storeNumbers  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[GetStoreLocationsRequest Class](getstorelocationsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoreLocationsRequest Overload](getstorelocationsrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

