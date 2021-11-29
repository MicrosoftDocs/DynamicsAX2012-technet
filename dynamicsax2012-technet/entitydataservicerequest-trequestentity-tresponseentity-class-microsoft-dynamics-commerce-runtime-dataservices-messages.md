---
title: EntityDataServiceRequest(TRequestEntity, TResponseEntity) Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityDataServiceRequest(TRequestEntity, TResponseEntity) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest`2
ms:mtpsurl: https://technet.microsoft.com/library/Dn998857(v=AX.60)
ms:contentKeyID: 65317541
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest`2
dev_langs:
- CSharp
- C++
- VB
---

# EntityDataServiceRequest(TRequestEntity, TResponseEntity) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Entity data service request template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class EntityDataServiceRequest(Of TRequestEntity, TResponseEntity As CommerceEntity) _
    Inherits DataRequest
'Usage
Dim instance As EntityDataServiceRequest(Of TRequestEntity, TResponseEntity)
```

``` csharp
[DataContractAttribute]
public class EntityDataServiceRequest<TRequestEntity, TResponseEntity> : DataRequest
where TResponseEntity : CommerceEntity
```

``` c++
[DataContractAttribute]
generic<typename TRequestEntity, typename TResponseEntity>
where TResponseEntity : CommerceEntity
public ref class EntityDataServiceRequest : public DataRequest
```

#### Type Parameters

  - TRequestEntity

<!-- end list -->

  - TResponseEntity

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.DataRequest](datarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceRequest\<TRequestEntity, TResponseEntity\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

