---
title: RequestContextExtensions.SetChannelId Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SetChannelId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetChannelId(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.setchannelid(v=AX.60)
ms:contentKeyID: 65318967
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetChannelId
dev_langs:
- CSharp
- C++
- VB
---

# SetChannelId Method

Sets the channel identifier for the current request. Used only for Login request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub SetChannelId ( _
    requestContext As RequestContext, _
    channelId As Long _
)
'Usage
Dim requestContext As RequestContext
Dim channelId As Long

requestContext.SetChannelId(channelId)
```

``` csharp
public static void SetChannelId(
    this RequestContext requestContext,
    long channelId
)
```

``` c++
[ExtensionAttribute]
public:
static void SetChannelId(
    RequestContext^ requestContext, 
    long long channelId
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

