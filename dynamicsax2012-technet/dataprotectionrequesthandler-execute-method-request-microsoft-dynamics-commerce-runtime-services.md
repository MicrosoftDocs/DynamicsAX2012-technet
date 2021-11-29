---
title: DataProtectionRequestHandler.Execute Method (Request) (Microsoft.Dynamics.Commerce.Runtime.Services)
TOCTitle: Execute Method (Request)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.DataProtectionRequestHandler.Execute(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.dataprotectionrequesthandler.execute(v=AX.60)
ms:contentKeyID: 65316888
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Execute Method (Request)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents the entry point of the request handler.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services](microsoft-dynamics-commerce-runtime-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone (in Microsoft.Dynamics.Commerce.Runtime.Services.WindowsPhone.dll)

## Syntax

``` vb
'Declaration
Public Function Execute ( _
    request As Request _
) As Response
'Usage
Dim instance As DataProtectionRequestHandler
Dim request As Request
Dim returnValue As Response

returnValue = instance.Execute(request)
```

``` csharp
public Response Execute(
    Request request
)
```

``` c++
public:
virtual Response^ Execute(
    Request^ request
) sealed
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Response](response-class-microsoft-dynamics-commerce-runtime-messages.md)  
The outgoing response message.  

#### Implements

[IRequestHandler.Execute(Request)](irequesthandler-execute-method-microsoft-dynamics-commerce-runtime-workflow.md)  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>The request is null.</p></td>
</tr>
<tr class="even">
<td><a href="https://technet.microsoft.com/library/8a7a4e64(v=ax.60)">NotSupportedException</a></td>
<td><p>The request type is not supported.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[DataProtectionRequestHandler Class](dataprotectionrequesthandler-class-microsoft-dynamics-commerce-runtime-services.md)

[Execute Overload](dataprotectionrequesthandler-execute-method-microsoft-dynamics-commerce-runtime-services.md)

[Microsoft.Dynamics.Commerce.Runtime.Services Namespace](microsoft-dynamics-commerce-runtime-services-namespace.md)

