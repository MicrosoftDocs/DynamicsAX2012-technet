---
title: EntityDataServiceResponse(TResponse, TOutParam) Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityDataServiceResponse(TResponse, TOutParam) Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{`0},`1[])
ms:mtpsurl: https://technet.microsoft.com/library/Dn968445(v=AX.60)
ms:contentKeyID: 65321060
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# EntityDataServiceResponse(TResponse, TOutParam) Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [EntityDataServiceResponse\<TResponse, TOutParam\>](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    entityCollection As ReadOnlyCollection(Of TResponse), _
    ParamArray outputParams As TOutParam() _
)
'Usage
Dim entityCollection As ReadOnlyCollection(Of TResponse)
Dim outputParams As TOutParam()

Dim instance As New EntityDataServiceResponse(entityCollection, _
    outputParams)
```

``` csharp
public EntityDataServiceResponse(
    ReadOnlyCollection<TResponse> entityCollection,
    params TOutParam[] outputParams
)
```

``` c++
public:
EntityDataServiceResponse(
    ReadOnlyCollection<TResponse>^ entityCollection, 
    ... array<TOutParam>^ outputParams
)
```

#### Parameters

  - entityCollection  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TResponse](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\>  

<!-- end list -->

  - outputParams  
    Type: [TOutParam](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\[\]  

## See Also

#### Reference

[EntityDataServiceResponse\<TResponse, TOutParam\> Class](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

