---
title: GetStoresRequest Constructor (ICollection(String), QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetStoresRequest Constructor (ICollection(String), QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetStoresRequest.#ctor(System.Collections.Generic.ICollection{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getstoresrequest.getstoresrequest(v=AX.60)
ms:contentKeyID: 65322424
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetStoresRequest Constructor (ICollection(String), QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    storeNumbers As ICollection(Of String), _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim storeNumbers As ICollection(Of String)
Dim queryResultSettings As QueryResultSettings

Dim instance As New GetStoresRequest(storeNumbers, _
    queryResultSettings)
```

``` csharp
public GetStoresRequest(
    ICollection<string> storeNumbers,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
GetStoresRequest(
    ICollection<String^>^ storeNumbers, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - storeNumbers  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetStoresRequest Class](getstoresrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetStoresRequest Overload](getstoresrequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

