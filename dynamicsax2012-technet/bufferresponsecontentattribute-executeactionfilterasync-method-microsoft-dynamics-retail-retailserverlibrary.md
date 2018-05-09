---
title: BufferResponseContentAttribute.ExecuteActionFilterAsync Method  (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: ExecuteActionFilterAsync Method
ms:assetid: M:Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute.ExecuteActionFilterAsync(System.Void,System.Net.Http.HttpResponseMessage,System.Web.Http.Controllers.HttpActionContext)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.bufferresponsecontentattribute.executeactionfilterasync(v=AX.60)
ms:contentKeyID: 62202789
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute.ExecuteActionFilterAsync
dev_langs:
- CSharp
- C++
- VB
---

# ExecuteActionFilterAsync Method

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
Public Function ExecuteActionFilterAsync ( _
    actionContext As Void, _
    cancellationToken As HttpResponseMessage, _
    continuation As HttpActionContext _
) As Task
'Usage
Dim instance As BufferResponseContentAttribute
Dim actionContext As Void
Dim cancellationToken As HttpResponseMessage
Dim continuation As HttpActionContext
Dim returnValue As Task

returnValue = instance.ExecuteActionFilterAsync(actionContext, _
    cancellationToken, continuation)
```

``` csharp
public Task ExecuteActionFilterAsync(
    void actionContext,
    HttpResponseMessage cancellationToken,
    HttpActionContext continuation
)
```

``` c++
public:
virtual Task^ ExecuteActionFilterAsync(
    void actionContext, 
    HttpResponseMessage^ cancellationToken, 
    HttpActionContext^ continuation
) sealed
```

#### Parameters

  - actionContext  
    Type: [System.Void](https://technet.microsoft.com/en-us/library/skf099af\(v=ax.60\))  

<!-- end list -->

  - cancellationToken  
    Type: HttpResponseMessage  

<!-- end list -->

  - continuation  
    Type: HttpActionContext  

#### Return Value

Type: Task  
Returns Task.  

## See Also

#### Reference

[BufferResponseContentAttribute Class](bufferresponsecontentattribute-class-microsoft-dynamics-retail-retailserverlibrary.md)

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

