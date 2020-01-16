---
title: CommerceRuntime.CreateRequestContext Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: CreateRequestContext Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.CreateRequestContext(Microsoft.Dynamics.Commerce.Runtime.Messages.Request)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.commerceruntime.createrequestcontext(v=AX.60)
ms:contentKeyID: 62213964
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.CommerceRuntime.CreateRequestContext
dev_langs:
- CSharp
- C++
- VB
---

# CreateRequestContext Method

Creates and populates the request context.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime (in Microsoft.Dynamics.Commerce.Runtime.dll)

## Syntax

``` vb
'Declaration
Public Function CreateRequestContext ( _
    request As Request _
) As RequestContext
'Usage
Dim instance As CommerceRuntime
Dim request As Request
Dim returnValue As RequestContext

returnValue = instance.CreateRequestContext(request)
```

``` csharp
public RequestContext CreateRequestContext(
    Request request
)
```

``` c++
public:
RequestContext^ CreateRequestContext(
    Request^ request
)
```

#### Parameters

  - request  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Messages.Request](request-class-microsoft-dynamics-commerce-runtime-messages.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  
The request context.  

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
<td><a href="datavalidationexception-class-microsoft-dynamics-commerce-runtime.md">DataValidationException</a></td>
<td><p>Thown if a terminal cannot be found.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[CommerceRuntime Class](commerceruntime-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

