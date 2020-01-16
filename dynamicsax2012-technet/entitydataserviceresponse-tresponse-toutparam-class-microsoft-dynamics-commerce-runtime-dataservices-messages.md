---
title: EntityDataServiceResponse(TResponse, TOutParam) Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityDataServiceResponse(TResponse, TOutParam) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2
ms:mtpsurl: https://technet.microsoft.com/library/Dn990291(v=AX.60)
ms:contentKeyID: 65321233
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`2
dev_langs:
- CSharp
- C++
- VB
---

# EntityDataServiceResponse(TResponse, TOutParam) Class

EntityDataServiceResponse contains the data service entity response.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class EntityDataServiceResponse(Of TResponse As CommerceEntity, TOutParam As CommerceEntity) _
    Inherits Response
'Usage
Dim instance As EntityDataServiceResponse(Of TResponse, TOutParam)
```

``` csharp
[DataContractAttribute]
public class EntityDataServiceResponse<TResponse, TOutParam> : Response
where TResponse : CommerceEntity
where TOutParam : CommerceEntity
```

``` c++
[DataContractAttribute]
generic<typename TResponse, typename TOutParam>
where TResponse : CommerceEntity
where TOutParam : CommerceEntity
public ref class EntityDataServiceResponse : public Response
```

#### Type Parameters

  - TResponse

<!-- end list -->

  - TOutParam

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse\<TResponse, TOutParam\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

