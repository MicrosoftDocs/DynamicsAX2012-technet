---
title: SearchStoreRequest Constructor (SearchStoreCriteria, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: SearchStoreRequest Constructor (SearchStoreCriteria, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.SearchStoreRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.searchstorerequest.searchstorerequest(v=AX.60)
ms:contentKeyID: 65323135
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# SearchStoreRequest Constructor (SearchStoreCriteria, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    queryCriteria As SearchStoreCriteria, _
    queryResultSettings As QueryResultSettings _
)
'Usage
Dim queryCriteria As SearchStoreCriteria
Dim queryResultSettings As QueryResultSettings

Dim instance As New SearchStoreRequest(queryCriteria, _
    queryResultSettings)
```

``` csharp
public SearchStoreRequest(
    SearchStoreCriteria queryCriteria,
    QueryResultSettings queryResultSettings
)
```

``` c++
public:
SearchStoreRequest(
    SearchStoreCriteria^ queryCriteria, 
    QueryResultSettings^ queryResultSettings
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchStoreCriteria](searchstorecriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - queryResultSettings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[SearchStoreRequest Class](searchstorerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[SearchStoreRequest Overload](searchstorerequest-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

