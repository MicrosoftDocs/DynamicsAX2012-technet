---
title: EntityDataServiceResponse(T) Constructor (ReadOnlyCollection(T)) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityDataServiceResponse(T) Constructor (ReadOnlyCollection(T))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`1.#ctor(System.Collections.ObjectModel.ReadOnlyCollection{`0})
ms:mtpsurl: https://technet.microsoft.com/library/Dn990601(v=AX.60)
ms:contentKeyID: 65321540
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# EntityDataServiceResponse(T) Constructor (ReadOnlyCollection(T))

Initializes a new instance of the [EntityDataServiceResponse\<T\>](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    entityCollection As ReadOnlyCollection(Of T) _
)
'Usage
Dim entityCollection As ReadOnlyCollection(Of T)

Dim instance As New EntityDataServiceResponse(entityCollection)
```

``` csharp
public EntityDataServiceResponse(
    ReadOnlyCollection<T> entityCollection
)
```

``` c++
public:
EntityDataServiceResponse(
    ReadOnlyCollection<T>^ entityCollection
)
```

#### Parameters

  - entityCollection  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[T](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\>  

## See Also

#### Reference

[EntityDataServiceResponse\<T\> Class](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[EntityDataServiceResponse\<T\> Overload](entitydataserviceresponse-t-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

