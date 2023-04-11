---
title: EntityDataServiceResponse(T).EntityCollection Property  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityCollection Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`1.EntityCollection
ms:mtpsurl: https://technet.microsoft.com/library/Dn967633(v=AX.60)
ms:contentKeyID: 65319504
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`1.EntityCollection
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
Public Property EntityCollection As ReadOnlyCollection(Of T)
    Get
    Private Set
'Usage
Dim instance As EntityDataServiceResponse
Dim value As ReadOnlyCollection(Of T)

value = instance.EntityCollection
```

``` csharp
[DataMemberAttribute]
public ReadOnlyCollection<T> EntityCollection { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReadOnlyCollection<T>^ EntityCollection {
    ReadOnlyCollection<T>^ get ();
    private: void set (ReadOnlyCollection<T>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[T](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[EntityDataServiceResponse\<T\> Class](entitydataserviceresponse-t-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

