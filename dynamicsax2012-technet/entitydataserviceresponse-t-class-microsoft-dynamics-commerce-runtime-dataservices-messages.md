---
title: EntityDataServiceResponse(T) Class (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: EntityDataServiceResponse(T) Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`1
ms:mtpsurl: https://technet.microsoft.com/library/Dn968671(v=AX.60)
ms:contentKeyID: 65321792
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse`1
dev_langs:
- CSharp
- C++
- VB
---

# EntityDataServiceResponse(T) Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

EntityDataServiceResponse contains the data service entity response.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class EntityDataServiceResponse(Of T) _
    Inherits Response
'Usage
Dim instance As EntityDataServiceResponse(Of T)
```

``` csharp
[DataContractAttribute]
public class EntityDataServiceResponse<T> : Response
```

``` c++
[DataContractAttribute]
generic<typename T>
public ref class EntityDataServiceResponse : public Response
```

#### Type Parameters

  - T

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.EntityDataServiceResponse\<T\>  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

