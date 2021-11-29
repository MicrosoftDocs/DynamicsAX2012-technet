---
title: EntityDataServiceResponse(TResponse, TOutParam).EntityCollection Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2.EntityCollection
ms:mtpsurl: https://technet.microsoft.com/library/Dn990558(v=AX.60)
ms:contentKeyID: 65321497
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2.EntityCollection
dev_langs:
- CSharp
- C++
- VB
---

# EntityCollection Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the entity read only collection.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntityCollection As ReadOnlyCollection(Of TResponse)
    Get
    Private Set
'Usage
Dim instance As EntityDataServiceResponse
Dim value As ReadOnlyCollection(Of TResponse)

value = instance.EntityCollection
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<TResponse> EntityCollection { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<TResponse>^ EntityCollection {
    ReadOnlyCollection<TResponse>^ get ();
    private: void set (ReadOnlyCollection<TResponse>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[TResponse](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[EntityDataServiceResponse\<TResponse, TOutParam\> Class](entitydataserviceresponse-tresponse-toutparam-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

